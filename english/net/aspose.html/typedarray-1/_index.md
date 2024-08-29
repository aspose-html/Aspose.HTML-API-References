---
title: TypedArrayT Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.TypedArray1T class. TypedArray objects present an array-like view of an underlying binary data buffer
type: docs
weight: 6040
url: /net/aspose.html/typedarray-1/
---
## TypedArray&lt;T&gt; class

TypedArray objects present an array-like view of an underlying binary data buffer.

```csharp
public abstract class TypedArray<T> : TypedArray
    where T : struct
```

| Parameter | Description |
| --- | --- |
| T | The data type. |

## Properties

| Name | Description |
| --- | --- |
| [Buffer](../../aspose.html/typedarray/buffer/) { get; } | Gets the ArrayBuffer referenced by this instance. |
| [ByteLength](../../aspose.html/typedarray/bytelength/) { get; } | Gets the byteLength accessor property represents the length of an ArrayBuffer in bytes. |
| [ByteOffset](../../aspose.html/typedarray/byteoffset/) { get; } | Gets the byteOffset from the start of referenced ArrayBuffer. |
| abstract [Item](../../aspose.html/typedarray-1/item/) { get; set; } | Gets or sets the !:T at the specified index. |
| [Length](../../aspose.html/typedarray/length/) { get; } | Gets the length of a typed array. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |

### See Also

* class [TypedArray](../typedarray/)
* namespace [Aspose.Html](../../aspose.html/)
* assembly [Aspose.HTML](../../)
