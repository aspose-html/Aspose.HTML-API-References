---
title: Node.ParentNode
second_title: Aspose.HTML for .NET API Reference
description: Node ParentNode property. The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree
type: docs
weight: 130
url: /net/aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```csharp
public Node ParentNode { get; }
```

### Property Value

A Node that is the parent of the current node. The parent of an element is an [`Element`](../../element/) node, a [`Document`](../../document/) node, or a [`DocumentFragment`](../../documentfragment/) node.

## Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### See Also

* class [Node](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
