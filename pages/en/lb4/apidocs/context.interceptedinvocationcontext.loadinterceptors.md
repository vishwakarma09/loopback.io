---
lang: en
title: 'API docs: context.interceptedinvocationcontext.loadinterceptors'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.interceptedinvocationcontext.loadinterceptors.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [InterceptedInvocationContext](./context.interceptedinvocationcontext.md) &gt; [loadInterceptors](./context.interceptedinvocationcontext.loadinterceptors.md)

## InterceptedInvocationContext.loadInterceptors() method

Load all interceptors for the given invocation context. It adds interceptors from possibly three sources: 1. method level `@intercept` 2. class level `@intercept` 3. global interceptors discovered in the context

<b>Signature:</b>

```typescript
loadInterceptors(): GenericInterceptorOrKey<InvocationContext>[];
```
<b>Returns:</b>

`GenericInterceptorOrKey<InvocationContext>[]`

