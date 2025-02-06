---
title: OutputStream Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.io.OutputStream class. A surrogate stream wraps the real output stream and controls access to it.OutputStream contains URI data that describes location of the output stream
type: docs
weight: 3770
url: /java/com.aspose.html.io/outputstream/
---
## OutputStream class

A surrogate stream wraps the real output stream and controls access to it.`OutputStream` contains URI data that describes location of the output stream.

```java
public class OutputStream : Stream
```

## Constructors

| Name | Description |
| --- | --- |
| [OutputStream](outputstream/)(Stream, String) | Initializes a new instance of the `OutputStream` class. |

## Properties

| Name | Description |
| --- | --- |
| [getCanRead](../../com.aspose.html.io/outputstream/canread/) Gets a value indicating whether the wrapped output stream supports reading. |
| [getCanSeek](../../com.aspose.html.io/outputstream/canseek/) Gets a value indicating whether the wrapped output stream supports seeking. |
| [getCanWrite](../../com.aspose.html.io/outputstream/canwrite/) Gets a value indicating whether the wrapped output stream supports writing. |
| [getLength](../../com.aspose.html.io/outputstream/length/) Gets the length in bytes of the wrapped output stream. |
[getPosition]
[setPosition] Gets or sets the position within the wrapped output stream. |
| [getUri](../../com.aspose.html.io/outputstream/uri/) Gets the URI of stream location. |

## Methods

| Name | Description |
| --- | --- |
| [close](../../com.aspose.html.io/outputstream/close/)() | Closes the wrapped output stream and current stream. |
| [flush](../../com.aspose.html.io/outputstream/flush/)() | Clears all buffers for the wrapped output stream and causes any buffered data to be written to the underlying device. |
| [read](../../com.aspose.html.io/outputstream/read/#read)(byte[], int, int) | Reads a sequence of bytes from the wrapped output stream and advances the position within the stream by the number of bytes read. |
| [seek](../../com.aspose.html.io/outputstream/seek/)(long, SeekOrigin) | Sets the position within the wrapped output stream. |
| [setLength](../../com.aspose.html.io/outputstream/setlength/)(long) | Sets the length of the wrapped output stream. |
| [write](../../com.aspose.html.io/outputstream/write/#write)(byte[], int, int) | Writes a sequence of bytes to the wrapped output stream and advances the current position within this stream by the number of bytes written. |

### See Also

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
