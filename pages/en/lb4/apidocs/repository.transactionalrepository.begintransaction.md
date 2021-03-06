---
lang: en
title: 'API docs: repository.transactionalrepository.begintransaction'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.transactionalrepository.begintransaction.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [TransactionalRepository](./repository.transactionalrepository.md) &gt; [beginTransaction](./repository.transactionalrepository.begintransaction.md)

## TransactionalRepository.beginTransaction() method

Begin a new Transaction

<b>Signature:</b>

```typescript
beginTransaction(options?: IsolationLevel | Options): Promise<Transaction>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  options | <code>IsolationLevel &#124; Options</code> | Options for the operations |

<b>Returns:</b>

`Promise<Transaction>`

Promise<Transaction> Promise that resolves to a new Transaction object


