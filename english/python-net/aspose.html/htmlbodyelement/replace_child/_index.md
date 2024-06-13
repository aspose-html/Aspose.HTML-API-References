﻿---
title: replace_child method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 350
url: /python-net/aspose.html/htmlbodyelement/replace_child/
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
| node | aspose.html.dom.Node | The new node. |
| child | aspose.html.dom.Node | The old child. |



### See Also
* module [`aspose.html`](../../)
* class [`HTMLBodyElement`](/html/python-net/aspose.html/htmlbodyelement)
* class [`Node`](/html/python-net/aspose.html.dom/node)