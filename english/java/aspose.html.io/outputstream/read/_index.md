---
title: OutputStream.Read
second_title: Aspose.HTML for Java API Reference
description: OutputStream method. Reads a sequence of bytes from the wrapped output stream and advances the position within the stream by the number of bytes read
type: docs
weight: 100
url: /java/com.aspose.html.io/outputstream/read/
---
## OutputStream.Read method

Reads a sequence of bytes from the wrapped output stream and advances the position within the stream by the number of bytes read.

```java
public int Read(byte[] buffer, int offset, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | Byte[] | An array of bytes. When this method returns, the buffer contains the specified byte array with the values between offset and (offset + count - 1) replaced by the bytes read from the the wrapped output stream. |
| offset | Int32 | The zero-based byte offset in buffer at which to begin storing the data read from the wrapped output stream. |
| count | Int32 | The maximum number of bytes to be read from the wrapped output stream. |

### Return Value

The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.

### See Also

* class [OutputStream](../)
* package [com.aspose.html.io](../../outputstream/)
* package [Aspose.HTML](../../../)
