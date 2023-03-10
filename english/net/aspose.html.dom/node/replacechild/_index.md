---
title: Node.ReplaceChild
second_title: Aspose.HTML for .NET API Reference
description: Node method. Replaces the child node oldChild with newChild in the list of children and returns the oldChild node. If newChild is a DocumentFragment object oldChild is replaced by all of the DocumentFragment children which are inserted in the same order. If the newChild is already in the tree it is first removed
type: docs
weight: 300
url: /net/aspose.html.dom/node/replacechild/
---
## Node.ReplaceChild method

Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../../documentfragment/) object, oldChild is replaced by all of the [`DocumentFragment`](../../documentfragment/) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed.

```csharp
public Node ReplaceChild(Node node, Node child)
```

| Parameter | Type | Description |
| --- | --- | --- |
| node | Node | The new node to replace oldChild. |
| child | Node | The child to be replaced. |

### Return Value

The replaced Node. This is the same node as oldChild.

### See Also

* class [Node](../)
* namespace [Aspose.Html.Dom](../../node/)
* assembly [Aspose.HTML](../../../)
