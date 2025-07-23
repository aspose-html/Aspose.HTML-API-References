---
title: Document.CreateElement
second_title: Aspose.HTML for .NET API Reference
description: Document CreateElement method. Creates the HTML element specified by localName or an HTMLUnknownElement if localName isnt recognized
type: docs
weight: 850
url: /net/aspose.html.dom/document/createelement/
---
## Document.CreateElement method

Creates the HTML element specified by localName, or an HTMLUnknownElement if localName isn't recognized.

```csharp
public Element CreateElement(string localName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | A string that specifies the type of element to be created. The nodeName of the created element is initialized with the value of localName. Don't use qualified names (like "html:a") with this method. When called on an HTML document, createElement() converts localName to lower case before creating the element. |

### Return Value

The new [`Element`](../../element/).

### See Also

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
