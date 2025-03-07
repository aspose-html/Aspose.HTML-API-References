---
title: Node.InsertBefore
second_title: Aspose.HTML for .NET API Reference
description: Node InsertBefore method. The insertBefore method of the Node interface inserts a node before a reference node as a child of a specified parent node
type: docs
weight: 200
url: /net/aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node.

If the given node already exists in the document, insertBefore() moves it from its current position to the new position. (That is, it will automatically be removed from its existing parent before appending it to the specified new parent.)

This means that a node cannot be in two locations of the document simultaneously.

```csharp
public Node InsertBefore(Node node, Node child)
```

| Parameter | Type | Description |
| --- | --- | --- |
| node | Node | The node to be inserted. |
| child | Node | The node before which newNode is inserted. If this is null, then newNode is inserted at the end of node's child nodes. |

### Return Value

Returns the added child (unless newNode is a [`DocumentFragment`](../../documentfragment/), in which case the empty [`DocumentFragment`](../../documentfragment/) is returned).

### See Also

* class [Node](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
