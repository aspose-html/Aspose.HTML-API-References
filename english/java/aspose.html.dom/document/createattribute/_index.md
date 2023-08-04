---
title: Document.CreateAttribute
second_title: Aspose.HTML for Java API Reference
description: Document method. The Document.createAttribute method creates a new attribute node and returns it. The object created a node implementing the Attr interface. The DOM does not enforce what sort of attributes can be added to a particular element in this manner
type: docs
weight: 790
url: /java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

The Document.createAttribute() method creates a new attribute node, and returns it. The object created a node implementing the [`Attr`](../../attr/) interface. The DOM does not enforce what sort of attributes can be added to a particular element in this manner.

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | name is a String containing the name of the attribute. |

### Return Value

A [`Attr`](../../attr/) node.

## Examples

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### See Also

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)
