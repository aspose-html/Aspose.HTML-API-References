---
title: INodeFilter.AcceptNode
second_title: Aspose.HTML for .NET API Reference
description: INodeFilter method. Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator it is not normally called directly from user code. Though you could do so if you wanted to use the same filter to guide your own application logic
type: docs
weight: 10
url: /net/aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator; it is not normally called directly from user code. (Though you could do so if you wanted to use the same filter to guide your own application logic.)

```csharp
public short AcceptNode(Node n)
```

| Parameter | Type | Description |
| --- | --- | --- |
| n | Node | node to check to see if it passes the filter or not. |

### Return Value

a constant to determine whether the node is accepted, rejected, or skipped, as defined above.

### See Also

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../)
* namespace [Aspose.Html.Dom.Traversal](../../../aspose.html.dom.traversal/)
* assembly [Aspose.HTML](../../../)
