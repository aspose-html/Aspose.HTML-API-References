---
title: OutputStream
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 3830
url: /net/aspose.html.io/outputstream/
---
## OutputStream class

A surrogate stream wraps the real output stream and controls access to it.[`OutputStream`](../outputstream) contains URI data that describes location of the output stream.

```csharp
public class OutputStream : Stream
```

## Constructors

| Name | Description |
| --- | --- |
| [OutputStream](outputstream)(Stream, string) | Initializes a new instance of the [`OutputStream`](../outputstream) class. |

## Properties

| Name | Description |
| --- | --- |
| override [CanRead](canread) { get; } | Gets a value indicating whether the wrapped output stream supports reading. |
| override [CanSeek](canseek) { get; } | Gets a value indicating whether the wrapped output stream supports seeking. |
| override [CanWrite](canwrite) { get; } | Gets a value indicating whether the wrapped output stream supports writing. |
| override [Length](length) { get; } | Gets the length in bytes of the wrapped output stream. |
| override [Position](position) { get; set; } | Gets or sets the position within the wrapped output stream. |
| [Uri](uri) { get; } | Gets the URI of stream location. |

## Methods

| Name | Description |
| --- | --- |
| override [Close](close)() | Closes the wrapped output stream and current stream. |
| override [Flush](flush)() | Clears all buffers for the wrapped output stream and causes any buffered data to be written to the underlying device. |
| override [Read](read)(byte[], int, int) | Reads a sequence of bytes from the wrapped output stream and advances the position within the stream by the number of bytes read. |
| override [Seek](seek)(long, SeekOrigin) | Sets the position within the wrapped output stream. |
| override [SetLength](setlength)(long) | Sets the length of the wrapped output stream. |
| override [Write](write)(byte[], int, int) | Writes a sequence of bytes to the wrapped output stream and advances the current position within this stream by the number of bytes written. |

### See Also

* namespace [Aspose.Html.IO](../../aspose.html.io)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->