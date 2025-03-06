---
title: Node.AppendChild
second_title: Aspose.HTML for .NET API Reference
description: Node AppendChild method. The appendChild method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document appendChild moves it from its current position to the new position there is no requirement to remove the node from its parent node before appending it to some other node
type: docs
weight: 170
url: /net/aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node).

This means that a node can't be in two points of the document simultaneously. So if the node already has a parent, the node is first removed, then appended at the new position. The [`Node.cloneNode()`](../clonenode/) method can be used to make a copy of the node before appending it under the new parent. Copies made with [`cloneNode`](../clonenode/) are not be automatically kept in sync.

```csharp
public Node AppendChild(Node node)
```

| Parameter | Type | Description |
| --- | --- | --- |
| node | Node | The node to append to the given parent node (commonly an element). |

### Return Value

A Node that is the appended child (aChild), except when aChild is a [`DocumentFragment`](../../documentfragment/), in which case the empty [`DocumentFragment`](../../documentfragment/) is returned.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | Thrown when the constraints of the DOM tree are violated. |

### See Also

* class [Node](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
