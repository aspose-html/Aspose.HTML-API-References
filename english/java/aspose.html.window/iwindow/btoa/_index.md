---
title: IWindow.Btoa
second_title: Aspose.HTML for Java API Reference
description: IWindow method. Takes the input data in the form of a Unicode String containing only characters in the range U0000 to U00FF each representing a binary byte with values 0x00 to 0xFF respectively and converts it to its base64 representation which it returns
type: docs

url: /java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Takes the input data, in the form of a Unicode String containing only characters in the range U+0000 to U+00FF, each representing a binary byte with values 0x00 to 0xFF respectively, and converts it to its base64 representation, which it returns.

```java
public String Btoa(String data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | String | The Unicode String containing only characters in the range U+0000 to U+00FF. |

### Return Value

The base64 String.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Throws an "InvalidCharacterError" DOMException exception if the input String contains any out-of-range characters. |

### See Also

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
