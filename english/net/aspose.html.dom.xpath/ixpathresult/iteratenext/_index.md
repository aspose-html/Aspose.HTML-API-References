---
title: IXPathResult.IterateNext
second_title: Aspose.HTML for .NET API Reference
description: IXPathResult IterateNext method. Iterates and returns the next node from the node set or null if there are no more nodes
type: docs
weight: 80
url: /net/aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Iterates and returns the next node from the node set or `null` if there are no more nodes.

```csharp
public Node IterateNext()
```

### Return Value

Returns the next node.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: raised if `resultType` is not `UnorderedNodeIterator` type or `OrderedNodeIterator` type. |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_STATE_ERR: The document has been mutated since the result was returned. |

### See Also

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Html.Dom.XPath](../../../aspose.html.dom.xpath/)
* assembly [Aspose.HTML](../../../)
