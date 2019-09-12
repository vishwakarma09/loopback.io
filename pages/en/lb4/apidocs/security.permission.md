---
lang: en
title: 'API docs: security.permission'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.security.permission.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/security](./security.md) &gt; [Permission](./security.permission.md)

## Permission class

`Permission` defines an action/access against a protected resource. It's the `what` for security.

There are three levels of permissions

- Resource level (Order, User) - Instance level (Order-0001, User-1001) - Property level (User-0001.email)

<b>Signature:</b>

```typescript
export declare class Permission 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [\[securityId\]](./security.permission._securityid_.md) |  | <code>string</code> |  |
|  [action](./security.permission.action.md) |  | <code>string</code> | Action or access of a protected resources, such as <code>read</code>, <code>create</code>, <code>update</code>, or <code>delete</code> |
|  [resourceId](./security.permission.resourceid.md) |  | <code>string</code> | Identity of a protected resource instance, such as <code>order-0001</code> or <code>customer-101</code> |
|  [resourceProperty](./security.permission.resourceproperty.md) |  | <code>string</code> | Property of a protected resource type/instance, such as <code>email</code> |
|  [resourceType](./security.permission.resourcetype.md) |  | <code>string</code> | Type of protected resource, such as <code>Order</code> or <code>Customer</code> |

## Example

- create a user (action: create, resource type: user) - read email of a user (action: read, resource property: user.email) - change email of a user (action: update, resource property: user.email) - cancel an order (action: delete, resource type: order)

