---
title: IBlob Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.IO.IBlob interface. A Blob object refers to a byte sequence and has a size attribute which is the total number of bytes in the byte sequence and a type attribute which is an ASCII-encoded string in lower case representing the media type of the byte sequence
type: docs
weight: 3930
url: /net/aspose.html.io/iblob/
---
## IBlob interface

A Blob object refers to a byte sequence, and has a size attribute which is the total number of bytes in the byte sequence, and a type attribute, which is an ASCII-encoded string in lower case representing the media type of the byte sequence.

```csharp
public interface IBlob
```

## Members
## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | Returns the size of the byte sequence in number of bytes. On getting, conforming user agents must return the total number of bytes that can be read by a FileReader or FileReaderSync object, or 0 if the Blob has no bytes to be read. |
| [Type](../../aspose.html.io/iblob/type/) { get; } | The ASCII-encoded string in lower case representing the media type of the Blob. On getting, user agents must return the type of a Blob as an ASCII-encoded string in lower case, such that when it is converted to a byte sequence, it is a parsable MIME type, or the empty string – 0 bytes – if the type cannot be determined. |

## Members
## Methods

| Name | Description |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(*ulong, ulong, string*) | Returns a new Blob object with bytes ranging from the optional start parameter up to but not including the optional end parameter, and with a type attribute that is the value of the optional contentType parameter. |

### See Also

* namespace [Aspose.Html.IO](../../aspose.html.io/)
* assembly [Aspose.HTML](../../)
