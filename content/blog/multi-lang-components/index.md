---
title: "Pulumi expands EKS support to Python, Go, and .NET"

# The date represents the post's publish date, and by default corresponds with
# the date this file was generated. Posts with future dates are visible in development,
# but excluded from production builds. Use the time and timezone-offset portions of
# of this value to schedule posts for publishing later.
date: 2020-11-19T16:48:16-07:00

# Draft posts are visible in development, but excluded from production builds.
# Set this property to `false` before submitting your post for review.
draft: true

meta_desc: Pulumi now supports EKS across Python, Go, .NET, and TypeScript.
meta_image: meta.png
authors:
    - levi-blackstone
tags:
    - eks
    - .net
    - python
    - go
    - typescript
---

Today we're excited to announce support for one of our most highly-requested features: multi-language components! Our
first multi-language component is the popular EKS package, which was previously only available for TypeScript. With the
[v0.21.0 release] (TODO link), teams can manage EKS clusters in their language of choice (Python, .NET, Go, and TypeScript)!

<!--more-->

Pulumi's support for many familiar programming languages means that your organization is free to choose which language
works best for each team. It's already possible to collaborate across languages by using separate stacks and referring to
them using Stack References (TODO link). Multi-language components take this one step further towards the vision of
"write once, use anywhere". Component authors broaden their reach across languages, and users benefit from the work
of a much larger community.

Multi-language component support allows component authors to project their API into all Pulumi-supported languages,
idiomatically, and without requiring knowledge of all of these languages. First-class authoring support for multi-language
components is in the works.

## Expanded EKS support

Our first multi-language component is EKS. Now you can easily create and manage a cluster in any of our supported
languages.

{{< chooser language "typescript,python,csharp,go" >}}

{{% choosable language typescript %}}

```typescript
import * as eks from "@pulumi/eks";

// Create an EKS cluster.
const cluster = new eks.Cluster("cluster", {
    instanceType: "t2.medium",
    desiredCapacity: 2,
    minSize: 1,
    maxSize: 2,
});

// Export the cluster's kubeconfig.
export const kubeconfig = cluster.kubeconfig;
```

{{% /choosable %}}

{{% choosable language python %}}

```python
import pulumi
import pulumi_eks as eks

# Create an EKS cluster.
cluster = eks.Cluster(
    "cluster", 
    instance_type="t2.medium",
    desired_capacity=2,
    min_size=1,
    max_size=2,
)

# Export the cluster's kubeconfig.
pulumi.export("kubeconfig", cluster.kubeconfig)
```

{{% /choosable %}}

{{% choosable language csharp %}}

```csharp
using System;
using System.Threading.Tasks;
using Pulumi;
using Pulumi.Eks.Cluster;

class EksStack : Stack
{
    public EksStack()
    {
        // Create an EKS cluster.
        var cluster = new Cluster("cluster", new ClusterArgs
        {
            InstanceType = "t2.medium",
            DesiredCapacity = 2,
            MinSize = 1,
            MaxSize = 2,
        });
        
        // Export the cluster's kubeconfig.
        [Output] public Output<string> Kubeconfig { get; set; }
    }

}

class Program
{
    static Task<int> Main(string[] args) => Deployment.RunAsync<EksStack>();
}
```

{{% /choosable %}}

{{% choosable language go %}}

```go
package main

import (
	"github.com/pulumi/pulumi-eks/sdk/go/eks/cluster"
	"github.com/pulumi/pulumi/sdk/v2/go/pulumi"
)

func main() {
	pulumi.Run(func(ctx *pulumi.Context) error {
		// Create an EKS cluster.
		cluster, err := cluster.NewCluster(ctx, "cluster",
			cluster.ClusterArgs{
				InstanceType:    pulumi.String("t2.medium"),
				DesiredCapacity: pulumi.Int(2),
				MinSize:         pulumi.Int(1),
				MaxSize:         pulumi.Int(2),
			},
		)
		if err != nil {
			return err
		}

		// Export the cluster's kubeconfig.
		ctx.Export("kubeconfig", cluster.Kubeconfig)

		return nil
	})
}
```

{{% /choosable %}}

{{< /chooser >}}

## Images

![Placeholder Image](meta.png)
