---
title: Uint8ClampedArray Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Uint8ClampedArray class. Represents an array of 8-bit unsigned integers clamped to 0-255 if you specified a value that is out of the range of 0255 0 or 255 will be set instead
type: docs
weight: 6090
url: /net/aspose.html/uint8clampedarray/
---
## Uint8ClampedArray class

Represents an array of 8-bit unsigned integers clamped to 0-255; if you specified a value that is out of the range of [0,255], 0 or 255 will be set instead;

```csharp
public class Uint8ClampedArray : TypedArray<byte>
```

## Constructors

| Name | Description |
| --- | --- |
| [Uint8ClampedArray](uint8clampedarray/#constructor)(*[ArrayBuffer](../arraybuffer/)*) | Initializes a new instance of the `Uint8ClampedArray` class. |
| [Uint8ClampedArray](uint8clampedarray/#constructor_3)(*byte[]*) | Initializes a new instance of the `Uint8ClampedArray` class. |
| [Uint8ClampedArray](uint8clampedarray/#constructor_4)(*int*) | Initializes a new instance of the `Uint8ClampedArray` class. |
| [Uint8ClampedArray](uint8clampedarray/#constructor_1)(*[ArrayBuffer](../arraybuffer/), int*) | Initializes a new instance of the `Uint8ClampedArray` class. |
| [Uint8ClampedArray](uint8clampedarray/#constructor_2)(*[ArrayBuffer](../arraybuffer/), int, int*) | Initializes a new instance of the `Uint8ClampedArray` class. |

## Properties

| Name | Description |
| --- | --- |
| [Buffer](../../aspose.html/typedarray/buffer/) { get; } | Gets the ArrayBuffer referenced by this instance. |
| [ByteLength](../../aspose.html/typedarray/bytelength/) { get; } | Gets the byteLength accessor property represents the length of an ArrayBuffer in bytes. |
| [ByteOffset](../../aspose.html/typedarray/byteoffset/) { get; } | Gets the byteOffset from the start of referenced ArrayBuffer. |
| override [Item](../../aspose.html/uint8clampedarray/item/) { get; set; } | Gets or sets the Byte at the specified index. |
| [Length](../../aspose.html/typedarray/length/) { get; } | Gets the length of a typed array. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object Type. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [BYTES_PER_ELEMENT](../../aspose.html/uint8clampedarray/bytes_per_element/) | The property represents the size in bytes of each element in an typed array. |

### See Also

* class [TypedArray&lt;T&gt;](../typedarray-1/)
* namespace [Aspose.Html](../../aspose.html/)
* assembly [Aspose.HTML](../../)
