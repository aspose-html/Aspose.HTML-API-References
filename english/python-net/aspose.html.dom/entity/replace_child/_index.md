---
title: replace_child method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 170
url: /python-net/aspose.html.dom/entity/replace_child/
is_root: false
---

## replace_child {#aspose.html.dom.Node-aspose.html.dom.Node}

Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. 
If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed.


### Returns 


Returns node


```python
def replace_child(self, node, child):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| node | [`Node`](/html/python-net/aspose.html.dom/node) | The new node. |
| child | [`Node`](/html/python-net/aspose.html.dom/node) | The old child. |



### See Also
* module [`aspose.html.dom`](../../)
* class [`Entity`](/html/python-net/aspose.html.dom/entity)
