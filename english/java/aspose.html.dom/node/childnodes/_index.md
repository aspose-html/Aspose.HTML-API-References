---
title: Node.ChildNodes
second_title: Aspose.HTML for Java API Reference
description: Node property. The read-only childNodes property of the Node interface returns a live NodeList of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements text and comments
type: docs
weight: 30
url: /net/com.aspose.html.dom/node/childnodes/
---
## Node.ChildNodes property

The read-only childNodes property of the Node interface returns a live [`NodeList`](../../../com.aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments.

Note: The [`NodeList`](../../../com.aspose.html.collections/nodelist/) being live means that its content is changed each time new children are added or removed.

```java
public NodeList ChildNodes { get; }
```

### Property Value

A live [`NodeList`](../../../com.aspose.html.collections/nodelist/) containing the children of the node.

Note: Several calls to childNodes return the same [`NodeList`](../../../com.aspose.html.collections/nodelist/).

## Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-childnodes](https://dom.spec.whatwg.org/#dom-node-childnodes).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### See Also

* class [NodeList](../../../com.aspose.html.collections/nodelist/)
* class [Node](../)
* package [com.aspose.html.Dom](../../node/)
* package [Aspose.HTML](../../../)
