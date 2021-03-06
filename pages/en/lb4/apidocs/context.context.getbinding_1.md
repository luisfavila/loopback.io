---
lang: en
title: 'API docs: context.context.getbinding_1'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.context.getbinding_1.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [Context](./context.context.md) &gt; [getBinding](./context.context.getbinding_1.md)

## Context.getBinding() method

Look up a binding by key in the context and its ancestors. If no matching binding is found and `options.optional` is not set to true, an error will be thrown.

<b>Signature:</b>

```typescript
getBinding<ValueType>(key: BindingAddress<ValueType>, options?: {
        optional?: boolean;
    }): Binding<ValueType> | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  key | <code>BindingAddress&lt;ValueType&gt;</code> | Binding key |
|  options | <code>{</code><br/><code>        optional?: boolean;</code><br/><code>    }</code> | Options to control if the binding is optional. If <code>options.optional</code> is set to true, the method will return <code>undefined</code> instead of throwing an error if the binding key is not found. |

<b>Returns:</b>

`Binding<ValueType> | undefined`


