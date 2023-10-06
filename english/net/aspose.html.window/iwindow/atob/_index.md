---
title: IWindow.Atob
second_title: Aspose.HTML for .NET API Reference
description: IWindow method. Takes the input data in the form of a Unicode string containing base64-encoded binary data decodes it and returns a string consisting of characters in the range U0000 to U00FF each representing a binary byte with values 0x00 to 0xFF respectively corresponding to that binary data
type: docs
weight: 120
url: /net/aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Takes the input data, in the form of a Unicode string containing base64-encoded binary data, decodes it, and returns a string consisting of characters in the range U+0000 to U+00FF, each representing a binary byte with values 0x00 to 0xFF respectively, corresponding to that binary data.

```csharp
public string Atob(string data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | String | The Unicode string containing base64-encoded binary data |

### Return Value

The string consisting of characters in the range U+0000 to U+00FF

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Throws an "InvalidCharacterError" DOMException if the input string is not valid base64 data. |

### See Also

* interface [IWindow](../)
* namespace [Aspose.Html.Window](../../../aspose.html.window/)
* assembly [Aspose.HTML](../../../)
