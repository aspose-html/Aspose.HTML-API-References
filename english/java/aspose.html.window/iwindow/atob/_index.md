---
title: IWindow.Atob
second_title: Aspose.HTML for Java API Reference
description: IWindow method. Takes the input data in the form of a Unicode String containing base64-encoded binary data decodes it and returns a String consisting of characters in the range U0000 to U00FF each representing a binary byte with values 0x00 to 0xFF respectively corresponding to that binary data
type: docs
weight: 120
url: /java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Takes the input data, in the form of a Unicode String containing base64-encoded binary data, decodes it, and returns a String consisting of characters in the range U+0000 to U+00FF, each representing a binary byte with values 0x00 to 0xFF respectively, corresponding to that binary data.

```java
public String Atob(String data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | String | The Unicode String containing base64-encoded binary data |

### Return Value

The String consisting of characters in the range U+0000 to U+00FF

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Throws an "InvalidCharacterError" DOMException if the input String is not valid base64 data. |

### See Also

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
