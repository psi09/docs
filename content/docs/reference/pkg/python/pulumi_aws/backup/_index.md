---
title: Module backup
title_tag: Module backup | Package pulumi_aws | Python SDK
linktitle: backup
notitle: true
block_external_search_index: true
---

{{< resource-docs-alert "aws" >}}

<div class="section" id="backup">
<h1>backup<a class="headerlink" href="#backup" title="Permalink to this headline">¶</a></h1>
<blockquote>
<div><p>This provider is a derived work of the <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws">Terraform Provider</a> distributed under
<a class="reference external" href="https://www.mozilla.org/en-US/MPL/2.0/">MPL 2.0</a>. If you encounter a bug or missing feature, first check the
<a class="reference external" href="https://github.com/pulumi/pulumi-aws/issues">pulumi/pulumi-aws repo</a>; however, if that doesn’t turn up
anything, please consult the source <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/issues">terraform-providers/terraform-provider-aws repo</a>.</p>
</div></blockquote>
<span class="target" id="module-pulumi_aws.backup"></span><dl class="py class">
<dt id="pulumi_aws.backup.AwaitableGetPlanResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">AwaitableGetPlanResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">plan_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.AwaitableGetPlanResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_aws.backup.AwaitableGetSelectionResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">AwaitableGetSelectionResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">iam_role_arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">plan_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resources</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">selection_id</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.AwaitableGetSelectionResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_aws.backup.AwaitableGetVaultResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">AwaitableGetVaultResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">kms_key_arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">recovery_points</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.AwaitableGetVaultResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_aws.backup.GetPlanResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">GetPlanResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">plan_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.GetPlanResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getPlan.</p>
<dl class="py attribute">
<dt id="pulumi_aws.backup.GetPlanResult.arn">
<code class="sig-name descname">arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetPlanResult.arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the backup plan.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetPlanResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetPlanResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetPlanResult.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetPlanResult.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The display name of a backup plan.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetPlanResult.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetPlanResult.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>Metadata that you can assign to help organize the plans you create.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetPlanResult.version">
<code class="sig-name descname">version</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetPlanResult.version" title="Permalink to this definition">¶</a></dt>
<dd><p>Unique, randomly generated, Unicode, UTF-8 encoded string that serves as the version ID of the backup plan.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_aws.backup.GetSelectionResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">GetSelectionResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">iam_role_arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">plan_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resources</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">selection_id</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.GetSelectionResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getSelection.</p>
<dl class="py attribute">
<dt id="pulumi_aws.backup.GetSelectionResult.iam_role_arn">
<code class="sig-name descname">iam_role_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetSelectionResult.iam_role_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the IAM role that AWS Backup uses to authenticate when restoring and backing up the target resource. See the <a class="reference external" href="https://docs.aws.amazon.com/aws-backup/latest/devguide/access-control.html#managed-policies">AWS Backup Developer Guide</a> for additional information about using AWS managed policies or creating custom policies attached to the IAM role.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetSelectionResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetSelectionResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetSelectionResult.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetSelectionResult.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The display name of a resource selection document.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetSelectionResult.resources">
<code class="sig-name descname">resources</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetSelectionResult.resources" title="Permalink to this definition">¶</a></dt>
<dd><p>An array of strings that either contain Amazon Resource Names (ARNs) or match patterns of resources to assign to a backup plan..</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_aws.backup.GetVaultResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">GetVaultResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">kms_key_arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">recovery_points</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.GetVaultResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getVault.</p>
<dl class="py attribute">
<dt id="pulumi_aws.backup.GetVaultResult.arn">
<code class="sig-name descname">arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetVaultResult.arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the vault.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetVaultResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetVaultResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetVaultResult.kms_key_arn">
<code class="sig-name descname">kms_key_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetVaultResult.kms_key_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The server-side encryption key that is used to protect your backups.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetVaultResult.recovery_points">
<code class="sig-name descname">recovery_points</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetVaultResult.recovery_points" title="Permalink to this definition">¶</a></dt>
<dd><p>The number of recovery points that are stored in a backup vault.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.GetVaultResult.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.GetVaultResult.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>Metadata that you can assign to help organize the resources that you create.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_aws.backup.Plan">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">Plan</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Plan" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides an AWS Backup plan resource.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_aws</span> <span class="k">as</span> <span class="nn">aws</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">backup</span><span class="o">.</span><span class="n">Plan</span><span class="p">(</span><span class="s2">&quot;example&quot;</span><span class="p">,</span> <span class="n">rules</span><span class="o">=</span><span class="p">[{</span>
    <span class="s2">&quot;rule_name&quot;</span><span class="p">:</span> <span class="s2">&quot;tf_example_backup_rule&quot;</span><span class="p">,</span>
    <span class="s2">&quot;schedule&quot;</span><span class="p">:</span> <span class="s2">&quot;cron(0 12 * * ? *)&quot;</span><span class="p">,</span>
    <span class="s2">&quot;targetVaultName&quot;</span><span class="p">:</span> <span class="n">aws_backup_vault</span><span class="p">[</span><span class="s2">&quot;test&quot;</span><span class="p">][</span><span class="s2">&quot;name&quot;</span><span class="p">],</span>
<span class="p">}])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The display name of a backup plan.</p></li>
<li><p><strong>rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A rule object that specifies a scheduled task that is used to back up a selection of resources.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Metadata that you can assign to help organize the plans you create.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">completionWindow</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The amount of time AWS Backup attempts a backup before canceling the job and returning an error.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">copyActions</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - Configuration block(s) with copy operation settings. Detailed below.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationVaultArn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - An Amazon Resource Name (ARN) that uniquely identifies the destination backup vault for the copied backup.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">lifecycle</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The lifecycle defines when a protected resource is copied over to a backup vault and when it expires.  Fields documented above.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">coldStorageAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after creation that a recovery point is moved to cold storage.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after creation that a recovery point is deleted. Must be 90 days greater than <code class="docutils literal notranslate"><span class="pre">cold_storage_after</span></code>.</p></li>
</ul>
</li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">lifecycle</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The lifecycle defines when a protected resource is copied over to a backup vault and when it expires.  Fields documented above.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">coldStorageAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after creation that a recovery point is moved to cold storage.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after creation that a recovery point is deleted. Must be 90 days greater than <code class="docutils literal notranslate"><span class="pre">cold_storage_after</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">recoveryPointTags</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Metadata that you can assign to help organize the resources that you create.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">rule_name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - An display name for a backup rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">schedule</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A CRON expression specifying when AWS Backup initiates a backup job.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">startWindow</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The amount of time in minutes before beginning a backup.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetVaultName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of a logical container where backups are stored.</p></li>
</ul>
<dl class="py attribute">
<dt id="pulumi_aws.backup.Plan.arn">
<code class="sig-name descname">arn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Plan.arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the backup plan.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Plan.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Plan.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The display name of a backup plan.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Plan.rules">
<code class="sig-name descname">rules</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Plan.rules" title="Permalink to this definition">¶</a></dt>
<dd><p>A rule object that specifies a scheduled task that is used to back up a selection of resources.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">completionWindow</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The amount of time AWS Backup attempts a backup before canceling the job and returning an error.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">copyActions</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - Configuration block(s) with copy operation settings. Detailed below.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationVaultArn</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - An Amazon Resource Name (ARN) that uniquely identifies the destination backup vault for the copied backup.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">lifecycle</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - The lifecycle defines when a protected resource is copied over to a backup vault and when it expires.  Fields documented above.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">coldStorageAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - Specifies the number of days after creation that a recovery point is moved to cold storage.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - Specifies the number of days after creation that a recovery point is deleted. Must be 90 days greater than <code class="docutils literal notranslate"><span class="pre">cold_storage_after</span></code>.</p></li>
</ul>
</li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">lifecycle</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - The lifecycle defines when a protected resource is copied over to a backup vault and when it expires.  Fields documented above.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">coldStorageAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - Specifies the number of days after creation that a recovery point is moved to cold storage.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - Specifies the number of days after creation that a recovery point is deleted. Must be 90 days greater than <code class="docutils literal notranslate"><span class="pre">cold_storage_after</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">recoveryPointTags</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Metadata that you can assign to help organize the resources that you create.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">rule_name</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - An display name for a backup rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">schedule</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A CRON expression specifying when AWS Backup initiates a backup job.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">startWindow</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The amount of time in minutes before beginning a backup.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetVaultName</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The name of a logical container where backups are stored.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Plan.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[dict]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Plan.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>Metadata that you can assign to help organize the plans you create.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Plan.version">
<code class="sig-name descname">version</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Plan.version" title="Permalink to this definition">¶</a></dt>
<dd><p>Unique, randomly generated, Unicode, UTF-8 encoded string that serves as the version ID of the backup plan.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Plan.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Plan.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Plan resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the backup plan.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The display name of a backup plan.</p></li>
<li><p><strong>rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A rule object that specifies a scheduled task that is used to back up a selection of resources.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Metadata that you can assign to help organize the plans you create.</p></li>
<li><p><strong>version</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Unique, randomly generated, Unicode, UTF-8 encoded string that serves as the version ID of the backup plan.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">completionWindow</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The amount of time AWS Backup attempts a backup before canceling the job and returning an error.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">copyActions</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - Configuration block(s) with copy operation settings. Detailed below.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationVaultArn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - An Amazon Resource Name (ARN) that uniquely identifies the destination backup vault for the copied backup.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">lifecycle</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The lifecycle defines when a protected resource is copied over to a backup vault and when it expires.  Fields documented above.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">coldStorageAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after creation that a recovery point is moved to cold storage.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after creation that a recovery point is deleted. Must be 90 days greater than <code class="docutils literal notranslate"><span class="pre">cold_storage_after</span></code>.</p></li>
</ul>
</li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">lifecycle</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The lifecycle defines when a protected resource is copied over to a backup vault and when it expires.  Fields documented above.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">coldStorageAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after creation that a recovery point is moved to cold storage.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteAfter</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after creation that a recovery point is deleted. Must be 90 days greater than <code class="docutils literal notranslate"><span class="pre">cold_storage_after</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">recoveryPointTags</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Metadata that you can assign to help organize the resources that you create.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">rule_name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - An display name for a backup rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">schedule</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A CRON expression specifying when AWS Backup initiates a backup job.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">startWindow</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The amount of time in minutes before beginning a backup.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetVaultName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of a logical container where backups are stored.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Plan.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Plan.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Plan.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Plan.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_aws.backup.Selection">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">Selection</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">iam_role_arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">plan_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resources</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">selection_tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Selection" title="Permalink to this definition">¶</a></dt>
<dd><p>Manages selection conditions for AWS Backup plan resources.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_aws</span> <span class="k">as</span> <span class="nn">aws</span>

<span class="n">example_role</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">iam</span><span class="o">.</span><span class="n">Role</span><span class="p">(</span><span class="s2">&quot;exampleRole&quot;</span><span class="p">,</span> <span class="n">assume_role_policy</span><span class="o">=</span><span class="s2">&quot;&quot;&quot;{</span>
<span class="s2">  &quot;Version&quot;: &quot;2012-10-17&quot;,</span>
<span class="s2">  &quot;Statement&quot;: [</span>
<span class="s2">    {</span>
<span class="s2">      &quot;Action&quot;: [&quot;sts:AssumeRole&quot;],</span>
<span class="s2">      &quot;Effect&quot;: &quot;allow&quot;,</span>
<span class="s2">      &quot;Principal&quot;: {</span>
<span class="s2">        &quot;Service&quot;: [&quot;backup.amazonaws.com&quot;]</span>
<span class="s2">      }</span>
<span class="s2">    }</span>
<span class="s2">  ]</span>
<span class="s2">}</span>

<span class="s2">&quot;&quot;&quot;</span><span class="p">)</span>
<span class="n">example_role_policy_attachment</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">iam</span><span class="o">.</span><span class="n">RolePolicyAttachment</span><span class="p">(</span><span class="s2">&quot;exampleRolePolicyAttachment&quot;</span><span class="p">,</span>
    <span class="n">policy_arn</span><span class="o">=</span><span class="s2">&quot;arn:aws:iam::aws:policy/service-role/AWSBackupServiceRolePolicyForBackup&quot;</span><span class="p">,</span>
    <span class="n">role</span><span class="o">=</span><span class="n">example_role</span><span class="o">.</span><span class="n">name</span><span class="p">)</span>
<span class="n">example_selection</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">backup</span><span class="o">.</span><span class="n">Selection</span><span class="p">(</span><span class="s2">&quot;exampleSelection&quot;</span><span class="p">,</span> <span class="n">iam_role_arn</span><span class="o">=</span><span class="n">example_role</span><span class="o">.</span><span class="n">arn</span><span class="p">)</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_aws</span> <span class="k">as</span> <span class="nn">aws</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">backup</span><span class="o">.</span><span class="n">Selection</span><span class="p">(</span><span class="s2">&quot;example&quot;</span><span class="p">,</span>
    <span class="n">iam_role_arn</span><span class="o">=</span><span class="n">aws_iam_role</span><span class="p">[</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;arn&quot;</span><span class="p">],</span>
    <span class="n">plan_id</span><span class="o">=</span><span class="n">aws_backup_plan</span><span class="p">[</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;id&quot;</span><span class="p">],</span>
    <span class="n">selection_tags</span><span class="o">=</span><span class="p">[{</span>
        <span class="s2">&quot;key&quot;</span><span class="p">:</span> <span class="s2">&quot;foo&quot;</span><span class="p">,</span>
        <span class="s2">&quot;type&quot;</span><span class="p">:</span> <span class="s2">&quot;STRINGEQUALS&quot;</span><span class="p">,</span>
        <span class="s2">&quot;value&quot;</span><span class="p">:</span> <span class="s2">&quot;bar&quot;</span><span class="p">,</span>
    <span class="p">}])</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_aws</span> <span class="k">as</span> <span class="nn">aws</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">backup</span><span class="o">.</span><span class="n">Selection</span><span class="p">(</span><span class="s2">&quot;example&quot;</span><span class="p">,</span>
    <span class="n">iam_role_arn</span><span class="o">=</span><span class="n">aws_iam_role</span><span class="p">[</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;arn&quot;</span><span class="p">],</span>
    <span class="n">plan_id</span><span class="o">=</span><span class="n">aws_backup_plan</span><span class="p">[</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;id&quot;</span><span class="p">],</span>
    <span class="n">resources</span><span class="o">=</span><span class="p">[</span>
        <span class="n">aws_db_instance</span><span class="p">[</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;arn&quot;</span><span class="p">],</span>
        <span class="n">aws_ebs_volume</span><span class="p">[</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;arn&quot;</span><span class="p">],</span>
        <span class="n">aws_efs_file_system</span><span class="p">[</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;arn&quot;</span><span class="p">],</span>
    <span class="p">])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>iam_role_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The ARN of the IAM role that AWS Backup uses to authenticate when restoring and backing up the target resource. See the <a class="reference external" href="https://docs.aws.amazon.com/aws-backup/latest/devguide/access-control.html#managed-policies">AWS Backup Developer Guide</a> for additional information about using AWS managed policies or creating custom policies attached to the IAM role.</p>
</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The display name of a resource selection document.</p></li>
<li><p><strong>plan_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The backup plan ID to be associated with the selection of resources.</p></li>
<li><p><strong>resources</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – An array of strings that either contain Amazon Resource Names (ARNs) or match patterns of resources to assign to a backup plan..</p></li>
<li><p><strong>selection_tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Tag-based conditions used to specify a set of resources to assign to a backup plan.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>selection_tags</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The key in a key-value pair.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - An operation, such as <code class="docutils literal notranslate"><span class="pre">StringEquals</span></code>, that is applied to a key-value pair used to filter resources in a selection.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">value</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The value in a key-value pair.</p></li>
</ul>
<dl class="py attribute">
<dt id="pulumi_aws.backup.Selection.iam_role_arn">
<code class="sig-name descname">iam_role_arn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Selection.iam_role_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the IAM role that AWS Backup uses to authenticate when restoring and backing up the target resource. See the <a class="reference external" href="https://docs.aws.amazon.com/aws-backup/latest/devguide/access-control.html#managed-policies">AWS Backup Developer Guide</a> for additional information about using AWS managed policies or creating custom policies attached to the IAM role.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Selection.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Selection.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The display name of a resource selection document.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Selection.plan_id">
<code class="sig-name descname">plan_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Selection.plan_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The backup plan ID to be associated with the selection of resources.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Selection.resources">
<code class="sig-name descname">resources</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Selection.resources" title="Permalink to this definition">¶</a></dt>
<dd><p>An array of strings that either contain Amazon Resource Names (ARNs) or match patterns of resources to assign to a backup plan..</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Selection.selection_tags">
<code class="sig-name descname">selection_tags</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Selection.selection_tags" title="Permalink to this definition">¶</a></dt>
<dd><p>Tag-based conditions used to specify a set of resources to assign to a backup plan.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The key in a key-value pair.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - An operation, such as <code class="docutils literal notranslate"><span class="pre">StringEquals</span></code>, that is applied to a key-value pair used to filter resources in a selection.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">value</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The value in a key-value pair.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Selection.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">iam_role_arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">plan_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resources</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">selection_tags</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Selection.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Selection resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>iam_role_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The ARN of the IAM role that AWS Backup uses to authenticate when restoring and backing up the target resource. See the <a class="reference external" href="https://docs.aws.amazon.com/aws-backup/latest/devguide/access-control.html#managed-policies">AWS Backup Developer Guide</a> for additional information about using AWS managed policies or creating custom policies attached to the IAM role.</p>
</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The display name of a resource selection document.</p></li>
<li><p><strong>plan_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The backup plan ID to be associated with the selection of resources.</p></li>
<li><p><strong>resources</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – An array of strings that either contain Amazon Resource Names (ARNs) or match patterns of resources to assign to a backup plan..</p></li>
<li><p><strong>selection_tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Tag-based conditions used to specify a set of resources to assign to a backup plan.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>selection_tags</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The key in a key-value pair.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - An operation, such as <code class="docutils literal notranslate"><span class="pre">StringEquals</span></code>, that is applied to a key-value pair used to filter resources in a selection.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">value</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The value in a key-value pair.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Selection.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Selection.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Selection.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Selection.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_aws.backup.Vault">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">Vault</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">kms_key_arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Vault" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides an AWS Backup vault resource.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_aws</span> <span class="k">as</span> <span class="nn">aws</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">backup</span><span class="o">.</span><span class="n">Vault</span><span class="p">(</span><span class="s2">&quot;example&quot;</span><span class="p">,</span> <span class="n">kms_key_arn</span><span class="o">=</span><span class="n">aws_kms_key</span><span class="p">[</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;arn&quot;</span><span class="p">])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>kms_key_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The server-side encryption key that is used to protect your backups.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the backup vault to create.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Metadata that you can assign to help organize the resources that you create.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_aws.backup.Vault.arn">
<code class="sig-name descname">arn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Vault.arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the vault.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Vault.kms_key_arn">
<code class="sig-name descname">kms_key_arn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Vault.kms_key_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The server-side encryption key that is used to protect your backups.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Vault.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Vault.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the backup vault to create.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Vault.recovery_points">
<code class="sig-name descname">recovery_points</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Vault.recovery_points" title="Permalink to this definition">¶</a></dt>
<dd><p>The number of recovery points that are stored in a backup vault.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_aws.backup.Vault.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[dict]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.backup.Vault.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>Metadata that you can assign to help organize the resources that you create.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Vault.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">kms_key_arn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">recovery_points</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Vault.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Vault resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the vault.</p></li>
<li><p><strong>kms_key_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The server-side encryption key that is used to protect your backups.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the backup vault to create.</p></li>
<li><p><strong>recovery_points</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The number of recovery points that are stored in a backup vault.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Metadata that you can assign to help organize the resources that you create.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Vault.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Vault.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_aws.backup.Vault.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.Vault.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py function">
<dt id="pulumi_aws.backup.get_plan">
<code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">get_plan</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">plan_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.get_plan" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to get information on an existing backup plan.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_aws</span> <span class="k">as</span> <span class="nn">aws</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">backup</span><span class="o">.</span><span class="n">get_plan</span><span class="p">(</span><span class="n">plan_id</span><span class="o">=</span><span class="s2">&quot;tf_example_backup_plan_id&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>plan_id</strong> (<em>str</em>) – The backup plan ID.</p></li>
<li><p><strong>tags</strong> (<em>dict</em>) – Metadata that you can assign to help organize the plans you create.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_aws.backup.get_selection">
<code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">get_selection</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">plan_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">selection_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.get_selection" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to get information on an existing backup selection.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_aws</span> <span class="k">as</span> <span class="nn">aws</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">backup</span><span class="o">.</span><span class="n">get_selection</span><span class="p">(</span><span class="n">plan_id</span><span class="o">=</span><span class="n">data</span><span class="p">[</span><span class="s2">&quot;aws_backup_plan&quot;</span><span class="p">][</span><span class="s2">&quot;example&quot;</span><span class="p">][</span><span class="s2">&quot;id&quot;</span><span class="p">],</span>
    <span class="n">selection_id</span><span class="o">=</span><span class="s2">&quot;selection-id-example&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>plan_id</strong> (<em>str</em>) – The backup plan ID associated with the selection of resources.</p></li>
<li><p><strong>selection_id</strong> (<em>str</em>) – The backup selection ID.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_aws.backup.get_vault">
<code class="sig-prename descclassname">pulumi_aws.backup.</code><code class="sig-name descname">get_vault</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.backup.get_vault" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to get information on an existing backup vault.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_aws</span> <span class="k">as</span> <span class="nn">aws</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">aws</span><span class="o">.</span><span class="n">backup</span><span class="o">.</span><span class="n">get_vault</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;example_backup_vault&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>name</strong> (<em>str</em>) – The name of the backup vault.</p></li>
<li><p><strong>tags</strong> (<em>dict</em>) – Metadata that you can assign to help organize the resources that you create.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

</div>
