---
title: "Secrets"
meta_desc: An in depth look at Pulumi secrets and their usage.
menu:
  intro:
    parent: concepts
    weight: 3

aliases: ["/docs/reference/secrets/"]
---

## Secrets

All resource input and output values are recorded as [`state`]({{< relref "/docs/intro/concepts/state/" >}}), and are stored in the Pulumi Service, a file, or a pluggable provider that you choose. These raw values are usually just server names, configuration settings, and so on. In some cases, however, these values contain sensitive data, such as database passwords or service tokens.

The Pulumi Service always transmits and stores entire state files securely; however, Pulumi also supports encrypting specific values as “secrets” for extra protection. Encryption ensures that these values never appear as plaintext in your state file. By default, the encryption method uses automatic, per-stack encryption keys provided by the Pulumi Service or you can use a [provider of your own choosing]({{< relref "/docs/intro/concepts/config#configuring-secrets-encryption" >}}) instead.

To encrypt a configuration setting before runtime, you can use the CLI command [`config set`]({{< relref "/docs/intro/concepts/config#configuration" >}}) command with a [`--secret`]({{< relref "/docs/intro/concepts/config#secrets" >}}) flag. You can also set a secret during runtime. Any [`Output<T>`]({{< relref "/docs/reference/pkg/python/pulumi/#outputs-and-inputs" >}}) value can be marked secret. If an output is a secret, any computed values derived from it—such as those derived through an [`apply`]({{< relref "/docs/reference/pkg/python/pulumi/#outputs-and-inputs" >}}) call —will also be marked secret. All these encrypted values are stored in your state file.

An `Output<T>`]({{< relref "/docs/reference/pkg/python/pulumi/#outputs-and-inputs" >}}) can be marked secret in a number of ways:

- By reading a secret from configuration using [`Config.get_secret`]({{< relref "/docs/reference/pkg/python/pulumi#pulumi.Config.get_secret" >}})  or [`Config.require_secret`]({{< relref "/docs/reference/pkg/python/pulumi/#pulumi.Config.require_secret" >}}).
- By creating a new secret value with [`Output.secret`]({{< relref "/docs/reference/pkg/python/pulumi#pulumi.Output.secret" >}}), such as when generating a new random password.
- By marking a resource as having secret properties using [`additionalSecretOutputs`]({{< relref "/docs/intro/concepts/programming-model#additionalsecretoutputs" >}}).
- By computing a secret value by using [`apply`]({{< relref "/docs/reference/pkg/python/pulumi/#outputs-and-inputs" >}}) or [`Output.all`]({{< relref "/reference/pkg/python/pulumi#pulumi.Output.all" >}}) with another secret value.

As soon as an `Output<T>` is marked secret, the Pulumi engine will encrypt it wherever it is stored.

> Note: Inside of an `apply` or `Output.all` call, your secret is decrypted into plaintext for use within the callback. It is up to your program to treat this value sensitively and only pass the plaintext value to code that you trust.

## Programmatically Creating Secrets

There are two ways to programmatically create secret values:

-  By using [`get_secret`]({{< relref "/docs/reference/pkg/python/pulumi#pulumi.Config.get_secret" >}}) or [`require_secret`]({{< relref "/docs/reference/pkg/python/pulumi#pulumi.Config.require_secret" >}}) when reading a value from config.
- By calling [`Output.secret`]({{< relref "/docs/reference/pkg/python/pulumi#pulumi.Output.secret" >}}) to construct a secret from an existing value.

As an example, let’s create an AWS Parameter Store secure value. Parameter Store is an AWS service that stores strings. Those strings can either be secret or not. To create an encrypted value, we need to pass an argument to initialize the store’s `value` property. Unfortunately, the obvious thing to do —passing a raw, unencrypted value— means that the value is also stored in the Pulumi state, unencrypted We need toe ensure that the value is a secret:

```python
cfg = pulumi.Config()
param = ssm.Parameter("a-secret-param",
    type="SecureString",
    value=cfg.require_secret("my-secret-value"))
```

The Parameter resource’s value property is encrypted in the Pulumi state file.

Pulumi tracks the transitive use of secrets, so that your secret won’t end up accidentally leaking into the state file. Tracking includes automatically marking data generated from secret inputs as secret themselves, as well as fully encrypting any resource properties that include secrets in them.

## How Secrets Relate to Outputs

Secrets have the same type, `Output<T>`, as do unencrypted resource outputs. The difference is that they are marked internally as needing encryption before persisting in the state file. When you combine an existing output that is marked as a secret using `apply`  or `Output.all` , the resulting output is also marked as a secret.

An `apply`’s callback is given the plaintext value of the underlying secret. Although Pulumi ensures that the value returned from an `apply`  on a secret is also marked as secret, Pulumi cannot guarantee that the `apply` callback itself will not expose the secret value —for instance, by explicitly printing the value to the console or saving it to a file. Be careful that you do not pass this plaintext value to code that might expose it.

Unlike regular outputs, secrets cannot be captured by the Pulumi closure serialization system for use in serverless code and doing so leads to an exception. We do plan to support this once we can ensure that the values will be persisted securely. See [pulumi/pulumi#2718](https://github.com/pulumi/pulumi/issues/2718).

## Explicitly Marking Resource Outputs as Secrets

It is possible to mark resource outputs as containing secrets. In this case, Pulumi will automatically treat those outputs as secrets and encrypt them in the state file and anywhere they flow to. To do so, use the [`additional secret outputs`]({{< relref "/docs/intro/concepts/programming-model#additionalsecretoutputs" >}}) option, as described above.
