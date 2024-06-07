---
title: pointer_before_reference_node property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.html.dom.traversal/inodeiterator/pointer_before_reference_node/
is_root: false
---

## pointer_before_reference_node property


The value of this flag determines whether the children of entity
reference nodes are visible to the iterator. If false, they  and
their descendants will be rejected. Note that this rejection takes
precedence over whatToShow and the filter. Also note
that this is currently the only situation where
NodeIterators may reject a complete subtree rather than
skipping individual nodes.
To produce a view of the document that has entity references
expanded and does not expose the entity reference node itself, use
the whatToShow flags to hide the entity reference node
and set expandEntityReferences to true when creating the
iterator. To produce a view of the document that has entity reference
nodes but no entity expansion, use the whatToShow flags
to show the entity reference node and set
expandEntityReferences to false.
### Definition:
```python
@property
def pointer_before_reference_node(self):
    ...
```

### See Also
* module [`aspose.html.dom.traversal`](../../)
* class [`INodeIterator`](/html/python-net/aspose.html.dom.traversal/inodeiterator)
