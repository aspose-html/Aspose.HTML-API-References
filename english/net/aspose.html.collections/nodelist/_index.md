---
title: NodeList Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Collections.NodeList class. The NodeList provides the abstraction of an ordered collection of nodes without defining or constraining how this collection is implemented
type: docs
weight: 50
url: /net/aspose.html.collections/nodelist/
---
## NodeList class

The NodeList provides the abstraction of an ordered collection of nodes, without defining or constraining how this collection is implemented.

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## Properties

| Name | Description |
| --- | --- |
| abstract [Item](../../aspose.html.collections/nodelist/item/) { get; } | Method returns the indexth item in the collection. If index is greater than or equal to the number of nodes in the list, this returns null. |
| abstract [Length](../../aspose.html.collections/nodelist/length/) { get; } | The number of nodes in the list. |

## Methods

| Name | Description |
| --- | --- |
| abstract [GetEnumerator](../../aspose.html.collections/nodelist/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| override [GetPlatformType](../../aspose.html.collections/nodelist/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |

### See Also

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Node](../../aspose.html.dom/node/)
* namespace [Aspose.Html.Collections](../../aspose.html.collections/)
* assembly [Aspose.HTML](../../)
