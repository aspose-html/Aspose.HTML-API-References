---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Aspose.HTML for Java API Reference
description: INodeIterator property. The value of this flag determines whether the children of entity reference nodes are visible to the iterator. If false they and their descendants will be rejected. Note that this rejection takes precedence over whatToShow and the filter. Also note that this is currently the only situation where NodeIterators may reject a complete subtree rather than skipping individual nodes. To produce a view of the document that has entity references expanded and does not expose the entity reference node itself use the whatToShow flags to hide the entity reference node and set expandEntityReferences to true when creating the iterator. To produce a view of the document that has entity reference nodes but no entity expansion use the whatToShow flags to show the entity reference node and set expandEntityReferences to false
type: docs

url: /java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

The value of this flag determines whether the children of entity reference nodes are visible to the iterator. If false, they and their descendants will be rejected. Note that this rejection takes precedence over whatToShow and the filter. Also note that this is currently the only situation where NodeIterators may reject a complete subtree rather than skipping individual nodes. To produce a view of the document that has entity references expanded and does not expose the entity reference node itself, use the whatToShow flags to hide the entity reference node and set expandEntityReferences to true when creating the iterator. To produce a view of the document that has entity reference nodes but no entity expansion, use the whatToShow flags to show the entity reference node and set expandEntityReferences to false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` if [expand entity references]; otherwise, `false`.

### See Also

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
