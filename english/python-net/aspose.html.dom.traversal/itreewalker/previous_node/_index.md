---
title: previous_node method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.html.dom.traversal/itreewalker/previous_node/
is_root: false
---

## previous_node {#}

Moves the TreeWalker to the previous visible node in
document order relative to the current node, and returns the new
node. If the current node has no previous node,  or if the search for
previousNode attempts to step upward from the
TreeWalker's root node,  returns
null, and retains the current node.


### Returns 


The new node, or null if the current node has no
previous node  in the TreeWalker's logical view.


```python
def previous_node(self):
    ...
```





### See Also
* module [`aspose.html.dom.traversal`](../../)
* class [`ITreeWalker`](/html/python-net/aspose.html.dom.traversal/itreewalker)
