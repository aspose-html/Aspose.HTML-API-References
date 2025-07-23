---
title: Node.ParentNode
second_title: Aspose.HTML for .NET API Reference
description: Node ParentNode property. Returns the parent of the specified node in the DOM tree
type: docs
weight: 130
url: /net/aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

Returns the parent of the specified node in the DOM tree.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so ParentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

A Node that is the parent of the current node. The parent of an element is an [`Element`](../../element/) node, a [`Document`](../../document/) node, or a [`DocumentFragment`](../../documentfragment/) node.

## Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).

### See Also

* class [Node](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
