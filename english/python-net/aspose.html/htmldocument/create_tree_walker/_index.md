﻿---
title: create_tree_walker method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 200
url: /python-net/aspose.html/htmldocument/create_tree_walker/
is_root: false
---

## create_tree_walker {#aspose.html.dom.Node}

Create a new TreeWalker over the subtree rooted at the
specified node.


### Returns 


The newly created TreeWalker.


```python
def create_tree_walker(self, root):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | aspose.html.dom.Node | node which will serve as the root for the
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is




## create_tree_walker {#aspose.html.dom.Node-int}

Create a new TreeWalker over the subtree rooted at the
specified node.


### Returns 


The newly created TreeWalker.


```python
def create_tree_walker(self, root, what_to_show):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | aspose.html.dom.Node | node which will serve as the root for the
| what_to_show | int | flag specifies which node types may appear in
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is




## create_tree_walker {#aspose.html.dom.Node-int-aspose.html.dom.traversal.INodeFilter}

Create a new TreeWalker over the subtree rooted at the
specified node.


### Returns 


The newly created TreeWalker.


```python
def create_tree_walker(self, root, what_to_show, filter):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| root | aspose.html.dom.Node | node which will serve as the root for the
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
* class [`ITreeWalker`](/html/python-net/aspose.html.dom.traversal/itreewalker)