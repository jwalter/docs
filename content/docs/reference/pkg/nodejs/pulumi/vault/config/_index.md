---
title: "Module config"
linktitle: "config"
meta_desc: "Explore members of the config module in the @pulumi/vault package."
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-vault)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-vault` repo](https://github.com/pulumi/pulumi-vault/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-vault` repo](https://github.com/terraform-providers/terraform-provider-vault/issues).







<h3>APIs</h3>
<ul class="api">
    <li><a href="#address"><span class="symbol api"></span>address</a></li>
    <li><a href="#caCertDir"><span class="symbol api"></span>caCertDir</a></li>
    <li><a href="#caCertFile"><span class="symbol api"></span>caCertFile</a></li>
    <li><a href="#clientAuths"><span class="symbol api"></span>clientAuths</a></li>
    <li><a href="#maxLeaseTtlSeconds"><span class="symbol api"></span>maxLeaseTtlSeconds</a></li>
    <li><a href="#maxRetries"><span class="symbol api"></span>maxRetries</a></li>
    <li><a href="#namespace"><span class="symbol api"></span>namespace</a></li>
    <li><a href="#skipTlsVerify"><span class="symbol api"></span>skipTlsVerify</a></li>
    <li><a href="#token"><span class="symbol api"></span>token</a></li>
</ul>




<h2 id="apis">APIs</h2>
<h3 class="pdoc-module-header" id="address" data-link-title="address">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L12">
        let <strong>address</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> address: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;address&#34;)</span>;</code></pre>

URL of the root of the target Vault server.

<h3 class="pdoc-module-header" id="caCertDir" data-link-title="caCertDir">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L16">
        let <strong>caCertDir</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> caCertDir: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;caCertDir&#34;)</span>;</code></pre>

Path to directory containing CA certificate files to validate the server's certificate.

<h3 class="pdoc-module-header" id="caCertFile" data-link-title="caCertFile">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L20">
        let <strong>caCertFile</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> caCertFile: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;caCertFile&#34;)</span>;</code></pre>

Path to a CA certificate file to validate the server's certificate.

<h3 class="pdoc-module-header" id="clientAuths" data-link-title="clientAuths">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L24">
        let <strong>clientAuths</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> clientAuths: {
    certFile: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>;
    keyFile: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>;
}[] | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;{ certFile: string, keyFile: string }[]&gt;(&#34;clientAuths&#34;)</span>;</code></pre>

Client authentication credentials.

<h3 class="pdoc-module-header" id="maxLeaseTtlSeconds" data-link-title="maxLeaseTtlSeconds">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L28">
        let <strong>maxLeaseTtlSeconds</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> maxLeaseTtlSeconds: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number'>number</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;number&gt;(&#34;maxLeaseTtlSeconds&#34;)</span>;</code></pre>

Maximum TTL for secret leases requested by this provider

<h3 class="pdoc-module-header" id="maxRetries" data-link-title="maxRetries">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L32">
        let <strong>maxRetries</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> maxRetries: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number'>number</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;number&gt;(&#34;maxRetries&#34;)</span>;</code></pre>

Maximum number of retries when a 5xx error code is encountered.

<h3 class="pdoc-module-header" id="namespace" data-link-title="namespace">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L36">
        let <strong>namespace</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> namespace: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;namespace&#34;)</span>;</code></pre>

The namespace to use. Available only for Vault Enterprise

<h3 class="pdoc-module-header" id="skipTlsVerify" data-link-title="skipTlsVerify">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L40">
        let <strong>skipTlsVerify</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> skipTlsVerify: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;skipTlsVerify&#34;)</span>;</code></pre>

Set this to true only if the target Vault server is an insecure development instance.

<h3 class="pdoc-module-header" id="token" data-link-title="token">
    <a href="https://github.com/pulumi/pulumi-vault/blob/d47da0d8366bfa08fd54899182f2e9341c58cc16/sdk/nodejs/config/vars.ts#L44">
        let <strong>token</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> token: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;token&#34;)</span>;</code></pre>

Token to use to authenticate to Vault.
