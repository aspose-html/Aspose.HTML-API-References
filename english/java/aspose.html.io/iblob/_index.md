---
title: IBlob Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.io.IBlob interface. A Blob object refers to a byte sequence and has a size attribute which is the total number of bytes in the byte sequence and a type attribute which is an ASCII-encoded String in lower case representing the media type of the byte sequence
type: docs
weight: 3930
url: /java/com.aspose.html.io/iblob/
---
## IBlob interface

A Blob object refers to a byte sequence, and has a size attribute which is the total number of bytes in the byte sequence, and a type attribute, which is an ASCII-encoded String in lower case representing the media type of the byte sequence.

```java
public interface IBlob
```

## Properties

| Name | Description |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) Returns the size of the byte sequence in number of bytes. On getting, conforming user agents must return the total number of bytes that can be read by a FileReader or FileReaderSync object, or 0 if the Blob has no bytes to be read. |
| [getType](../../com.aspose.html.io/iblob/type/) The ASCII-encoded String in lower case representing the media type of the Blob. On getting, user agents must return the type of a Blob as an ASCII-encoded String in lower case, such that when it is converted to a byte sequence, it is a parsable MIME type, or the empty String – 0 bytes – if the type cannot be determined. |

## Methods

| Name | Description |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | Returns a new Blob object with bytes ranging from the optional start parameter up to but not including the optional end parameter, and with a type attribute that is the value of the optional contentType parameter. |

### See Also

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
