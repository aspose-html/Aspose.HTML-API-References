---
title: current_node property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 100
url: /aspose.html.dom.traversal/itreewalker/current_node/
is_root: false
---

## current_node property


The node at which the TreeWalker is currently positioned.
Alterations to the DOM tree may cause the current node to no longer
be accepted by the TreeWalker's associated filter.
currentNode may also be explicitly set to any node,
whether or not it is within the subtree specified by the
root node or would be accepted by the filter and
whatToShow flags. Further traversal occurs relative to
currentNode even if it is not part of the current view,
by applying the filters in the requested direction; if no traversal
is possible, currentNode is not changed.
### Definition:
```python
@property
def current_node(self):
    ...
@current_node.setter
def current_node(self, value):
    ...
```

### See Also
* module [`aspose.html.dom.traversal`](../../)
* class [`ITreeWalker`](/html/python-net/aspose.html.dom.traversal/itreewalker)
* class [`Node`](/html/python-net/aspose.html.dom/node)
