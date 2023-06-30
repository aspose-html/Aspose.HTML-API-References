---
title: IWindow.Btoa
second_title: Aspose.HTML for .NET API Reference
description: IWindow method. Takes the input data in the form of a Unicode string containing only characters in the range U0000 to U00FF each representing a binary byte with values 0x00 to 0xFF respectively and converts it to its base64 representation which it returns
type: docs
weight: 120
url: /net/aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Takes the input data, in the form of a Unicode string containing only characters in the range U+0000 to U+00FF, each representing a binary byte with values 0x00 to 0xFF respectively, and converts it to its base64 representation, which it returns.

```csharp
public string Btoa(string data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | String | The Unicode string containing only characters in the range U+0000 to U+00FF. |

### Return Value

The base64 string.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Throws an "InvalidCharacterError" DOMException exception if the input string contains any out-of-range characters. |

### See Also

* interface [IWindow](../)
* namespace [Aspose.Html.Window](../../../aspose.html.window/)
* assembly [Aspose.HTML](../../../)
