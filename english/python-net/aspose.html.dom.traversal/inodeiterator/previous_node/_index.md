---
title: previous_node method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.html.dom.traversal/inodeiterator/previous_node/
is_root: false
---

## previous_node {#}

Returns the previous node in the set and moves the position of the
NodeIterator backwards in the set.


### Returns 


The previous Node in the set being iterated over,
or null if there are no more members in that set.


```python
def previous_node(self):
    ...
```


### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INVALID_STATE_ERR: Raised if this method is called after the<br/>detach method was invoked. |





### See Also
* module [`aspose.html.dom.traversal`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`INodeIterator`](/html/python-net/aspose.html.dom.traversal/inodeiterator)
