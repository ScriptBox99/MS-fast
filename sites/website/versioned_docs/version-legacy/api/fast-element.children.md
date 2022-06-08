---
id: fast-element.children
title: children() function
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-element](./fast-element.md) &gt; [children](./fast-element.children.md)

## children() function

A directive that observes the `childNodes` of an element and updates a property whenever they change.

<b>Signature:</b>

```typescript
export declare function children<T = any>(propertyOrOptions: (keyof T & string) | ChildrenBehaviorOptions<keyof T & string>): CaptureType<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  propertyOrOptions | (keyof T &amp; string) \| [ChildrenBehaviorOptions](./fast-element.childrenbehavioroptions.md)<!-- -->&lt;keyof T &amp; string&gt; | The options used to configure child node observation. |

<b>Returns:</b>

[CaptureType](./fast-element.capturetype.md)<!-- -->&lt;T&gt;