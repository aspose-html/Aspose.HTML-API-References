---
title: Document.CreateAttribute
second_title: Aspose.HTML for .NET API Reference
description: Document CreateAttribute method. The Document.createAttribute method creates a new attribute node and returns it. The object created a node implementing the Attr interface. The DOM does not enforce what sort of attributes can be added to a particular element in this manner
type: docs
weight: 790
url: /net/aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

The Document.createAttribute() method creates a new attribute node, and returns it. The object created a node implementing the [`Attr`](../../attr/) interface. The DOM does not enforce what sort of attributes can be added to a particular element in this manner.

```csharp
public Attr CreateAttribute(string localName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | name is a string containing the name of the attribute. |

### Return Value

A [`Attr`](../../attr/) node.

## Examples

```csharp
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### See Also

* class [Attr](../../attr/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
