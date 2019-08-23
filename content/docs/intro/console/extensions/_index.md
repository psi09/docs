---
title: "Integrations and Extensions"

menu:
    intro:
        parent: console
        identifier: extensions
        weight: 6
---

The Pulumi Console provides ways for you to integrate with popular CI/CD platforms and services, and access your data to power workflows.


{{< notes >}}
Some features are only found in the Pulumi Team and Enterprise editions. See
<a href="{{< relref "editions" >}}">Pulumi Product Editions</a> for more information.
{{< /notes >}}

## Webhooks

Pulumi [webhooks]({{< relref "webhooks" >}}) enable you to trigger custom workflows
in response to events from your Pulumi organization or stack. For example, posting
a notification that production has been updated successfully.

## Project Templates

If you want to share a common cloud application, you can create a reusable
[template]({{< relref "pulumi-button" >}}) to share with other developers.

## Resources

If you are looking for inspiration on how to build extensions using Pulumi,
see the following resources:

- [Building new Pulumi projects and stacks from templates]({{< relref "building-new-pulumi-projects-and-stacks-from-templates" >}})
- [Creating and Reusing Cloud Components using Package Managers]({{< relref "creating-and-reusing-cloud-components-using-package-managers" >}})
- [Managing GitHub Webhooks with Pulumi]({{< relref "managing-github-webhooks-with-pulumi" >}})