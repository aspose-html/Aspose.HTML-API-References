﻿---
title: create_node_iterator method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 160
url: /python-net/aspose.html/htmldocument/create_node_iterator/
is_root: false
---

## create_node_iterator {#aspose.html.dom.Node}

Create a new NodeIterator over the subtree rooted at the
specified node.


### Returns 


The newly created NodeIterator.


```python
def create_node_iterator(self, root):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | aspose.html.dom.Node | node which will be iterated together with its children.
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is




## create_node_iterator {#aspose.html.dom.Node-int}

Create a new NodeIterator over the subtree rooted at the
specified node.


### Returns 


The newly created NodeIterator.


```python
def create_node_iterator(self, root, what_to_show):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | aspose.html.dom.Node | node which will be iterated together with its children.
| what_to_show | int | flag specifies which node types may appear in
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is




## create_node_iterator {#aspose.html.dom.Node-int-aspose.html.dom.traversal.INodeFilter}

Create a new NodeIterator over the subtree rooted at the
specified node.


### Returns 


The newly created NodeIterator.


```python
def create_node_iterator(self, root, what_to_show, filter):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | aspose.html.dom.Node | node which will be iterated together with its children.
| what_to_show | int | flag specifies which node types may appear in
| filter | aspose.html.dom.traversal.INodeFilter | NodeFilter to be used with this
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`HTMLDocument`](/html/python-net/aspose.html/htmldocument)
* class [`INodeIterator`](/html/python-net/aspose.html.dom.traversal/inodeiterator)