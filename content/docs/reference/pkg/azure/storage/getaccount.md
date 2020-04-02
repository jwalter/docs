
---
title: "GetAccount"
block_external_search_index: true
---

Use this data source to access information about an existing Storage Account.

> This content is derived from https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/d/storage_account.html.markdown.





## Using GetAccount

{{< chooser language "javascript,typescript,python,go,csharp" / >}}


{{% choosable language typescript %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getAccount<span class="p">(</span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/storage/#GetAccountArgs">GetAccountArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azure/storage/#GetAccountResult">GetAccountResult</a></span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">function </span> get_account(</span>name=None<span class="p">, </span>resource_group_name=None<span class="p">, </span>opts=None<span class="p">)</span></code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupAccount<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#LookupAccountArgs">LookupAccountArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#LookupAccountResult">LookupAccountResult</a></span>, error)</span></code></pre></div>
{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetAccount </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Storage.GetAccountResult.html">GetAccountResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Azure/Pulumi.Azure.Storage.GetAccountArgs.html">GetAccountArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span>? <span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the Storage Account
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the resource group the Storage Account is located in.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the Storage Account
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the resource group the Storage Account is located in.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the Storage Account
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the resource group the Storage Account is located in.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the Storage Account
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the resource group the Storage Account is located in.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## GetAccount Result

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The access tier for `BlobStorage` accounts.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Kind of account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of replication used for this storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Tier of this storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Custom<wbr>Domains</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getaccountcustomdomain">List&lt;Get<wbr>Account<wbr>Custom<wbr>Domain&gt;</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is traffic only allowed via HTTPS? See [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}id is the provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled?
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Azure location where the Storage Account exists
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Custom Domain Name used for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary access key for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary location of the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary location of the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string></span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The access tier for `BlobStorage` accounts.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Kind of account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of replication used for this storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Tier of this storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Custom<wbr>Domains</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getaccountcustomdomain">[]Get<wbr>Account<wbr>Custom<wbr>Domain</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is traffic only allowed via HTTPS? See [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}id is the provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled?
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Azure location where the Storage Account exists
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Custom Domain Name used for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary access key for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary location of the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary location of the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>access<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The access tier for `BlobStorage` accounts.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account<wbr>Kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Kind of account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account<wbr>Replication<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of replication used for this storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account<wbr>Tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Tier of this storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>custom<wbr>Domains</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getaccountcustomdomain">Get<wbr>Account<wbr>Custom<wbr>Domain[]</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable<wbr>Https<wbr>Traffic<wbr>Only</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Is traffic only allowed via HTTPS? See [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}id is the provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>is<wbr>Hns<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled?
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Azure location where the Storage Account exists
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The Custom Domain Name used for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary access key for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The primary location of the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Blob<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Blob<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Blob<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Connection<wbr>String</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Dfs<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Dfs<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>File<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>File<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Location</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The secondary location of the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Queue<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Queue<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Table<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Table<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Web<wbr>Endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary<wbr>Web<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>access_<wbr>tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The access tier for `BlobStorage` accounts.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account_<wbr>kind</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Kind of account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account_<wbr>replication_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of replication used for this storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>account_<wbr>tier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Tier of this storage account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>custom_<wbr>domains</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getaccountcustomdomain">List[Get<wbr>Account<wbr>Custom<wbr>Domain]</a></span>
    </dt>
    <dd>{{% md %}}A `custom_domain` block as documented below.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable_<wbr>https_<wbr>traffic_<wbr>only</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is traffic only allowed via HTTPS? See [here](https://docs.microsoft.com/en-us/azure/storage/storage-require-secure-transfer/)
for more information.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}id is the provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>is_<wbr>hns_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Is Hierarchical Namespace enabled?
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Azure location where the Storage Account exists
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Custom Domain Name used for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>access_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The primary access key for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>blob_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary blob location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>blob_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>blob_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the primary location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>dfs_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>dfs_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>file_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>file_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The primary location of the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>queue_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>queue_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>table_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>table_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>web_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>primary_<wbr>web_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the primary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>resource_<wbr>group_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>access_<wbr>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The secondary access key for the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>blob_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary blob location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>blob_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>blob_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for blob storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>connection_<wbr>string</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The connection string associated with the secondary location
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>dfs_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>dfs_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for DFS storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>file_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>file_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for file storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>location</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The secondary location of the Storage Account.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>queue_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>queue_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for queue storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>table_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>table_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for table storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>web_<wbr>endpoint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The endpoint URL for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>secondary_<wbr>web_<wbr>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hostname with port if applicable for web storage in the secondary location.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}A mapping of tags to assigned to the resource.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Supporting Types

<h4>Get<wbr>Account<wbr>Custom<wbr>Domain</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/azure/types/output/#GetAccountCustomDomain">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azure/sdk/go/azure/storage?tab=doc#GetAccountCustomDomain">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the Storage Account
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the Storage Account
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the Storage Account
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Specifies the name of the Storage Account
{{% /md %}}</dd>

</dl>
{{% /choosable %}}






