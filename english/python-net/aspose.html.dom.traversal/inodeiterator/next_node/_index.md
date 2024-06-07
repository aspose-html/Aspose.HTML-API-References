---
title: next_node method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.html.dom.traversal/inodeiterator/next_node/
is_root: false
---

## next_node {#}

Returns the next node in the set and advances the position of the
iterator in the set. After a NodeIterator is created,
the first call to nextNode() returns the first node in
the set.


### Returns 


The next Node in the set being iterated over, or
null if there are no more members in that set.


```python
def next_node(self):
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
