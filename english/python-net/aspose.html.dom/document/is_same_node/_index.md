---
title: is_same_node method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 330
url: /aspose.html.dom/document/is_same_node/
is_root: false
---

## is_same_node {#aspose.html.dom.Node}

Returns whether this node is the same node as the given one. 
This method provides a way to determine whether two Node references returned by the implementation reference the same object. When two Node references are references to the same object, even if through a proxy, the references may be used completely interchangeably, such that all attributes have the same values and calling the same DOM method on either reference always has exactly the same effect.


### Returns 


`true` if [is same node] [the specified other]; otherwise, `false`.


```python
def is_same_node(self, other_node):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| other_node | [`Node`](/html/python-net/aspose.html.dom/node) | The other node. |



### See Also
* module [`aspose.html.dom`](../../)
* class [`Document`](/html/python-net/aspose.html.dom/document)
