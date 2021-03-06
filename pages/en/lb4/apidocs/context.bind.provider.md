---
lang: en
title: 'API docs: context.bind.provider'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/context
permalink: /doc/en/lb4/apidocs.context.bind.provider.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [bind](./context.bind.md) &gt; [provider](./context.bind.provider.md)

## bind.provider() function

`@bind.provider` to denote a provider class

A list of binding scope/tags or template functions to configure the binding

<b>Signature:</b>

```typescript
function provider(...specs: BindingSpec[]): (target: Constructor<unknown>) => void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  specs | [BindingSpec](./context.bindingspec.md)<!-- -->\[\] |  |

<b>Returns:</b>

(target: [Constructor](./context.constructor.md)<!-- -->&lt;unknown&gt;) =&gt; void


