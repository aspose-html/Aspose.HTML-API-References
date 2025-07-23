---
title: append_child method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.html/htmladdresselement/append_child/
is_root: false
---

## append_child {#aspose.html.dom.Node}

Adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, [`Node.append_child`](/html/python-net/aspose.html.dom/node/append_child) moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node).


This means that a node can't be in two points of the document simultaneously. So if the node already has a parent, the node is first removed, then appended at the new position. The [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) method can be used to make a copy of the node before appending it under the new parent. Copies made with [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) are not be automatically kept in sync.


### Returns 


A Node that is the appended child, except when child is a [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment), in which case the empty [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment) is returned.


```python
def append_child(self, node):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| node | aspose.html.dom.Node | The node to append to the given parent node (commonly an element). |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Thrown when the constraints of the DOM tree are violated. |





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment)
* class [`HTMLAddressElement`](/html/python-net/aspose.html/htmladdresselement)
* class [`Node`](/html/python-net/aspose.html.dom/node)
