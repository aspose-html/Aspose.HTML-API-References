---
title: INodeIterator.NextNode
second_title: Aspose.HTML for .NET API Reference
description: INodeIterator NextNode method. Returns the next node in the set and advances the position of the iterator in the set. After a NodeIterator is created the first call to nextNode returns the first node in the set
type: docs
weight: 40
url: /net/aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Returns the next node in the set and advances the position of the iterator in the set. After a NodeIterator is created, the first call to nextNode() returns the first node in the set.

```csharp
public Node NextNode()
```

### Return Value

The next Node in the set being iterated over, or null if there are no more members in that set.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_STATE_ERR: Raised if this method is called after the detach method was invoked. |

### See Also

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeIterator](../)
* namespace [Aspose.Html.Dom.Traversal](../../../aspose.html.dom.traversal/)
* assembly [Aspose.HTML](../../../)
