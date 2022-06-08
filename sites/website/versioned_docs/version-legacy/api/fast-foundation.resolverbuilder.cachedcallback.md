---
id: fast-foundation.resolverbuilder.cachedcallback
title: ResolverBuilder.cachedCallback() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-foundation](./fast-foundation.md) &gt; [ResolverBuilder](./fast-foundation.resolverbuilder.md) &gt; [cachedCallback](./fast-foundation.resolverbuilder.cachedcallback.md)

## ResolverBuilder.cachedCallback() method

Creates a resolver that invokes a callback function the first time that a dependency resolution is requested. The returned value is then cached and provided for all subsequent requests.

<b>Signature:</b>

```typescript
cachedCallback(value: ResolveCallback<K>): Resolver<K>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  value | [ResolveCallback](./fast-foundation.resolvecallback.md)<!-- -->&lt;K&gt; | The callback to call during the first resolution. |

<b>Returns:</b>

[Resolver](./fast-foundation.resolver.md)<!-- -->&lt;K&gt;

The resolver.