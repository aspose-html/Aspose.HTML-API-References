---
title: create_node_iterator method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 160
url: /aspose.html.dom/document/create_node_iterator/
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
| root | [`Node`](/html/python-net/aspose.html.dom/node) | node which will be iterated together with its children.<br/>The iterator is initially positioned just before this node. The<br/>whatToShow flags and the filter, if any, are not<br/>considered when setting this position. The root must not be<br/>null. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is<br/>null. |




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
| root | [`Node`](/html/python-net/aspose.html.dom/node) | node which will be iterated together with its children.<br/>The iterator is initially positioned just before this node. The<br/>whatToShow flags and the filter, if any, are not<br/>considered when setting this position. The root must not be<br/>null. |
| what_to_show | int | flag specifies which node types may appear in<br/>the logical view of the tree presented by the iterator. See the<br/>description of NodeFilter for the set of possible<br/>SHOW_ values.These flags can be combined using<br/>OR. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is<br/>null. |




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
| root | [`Node`](/html/python-net/aspose.html.dom/node) | node which will be iterated together with its children.<br/>The iterator is initially positioned just before this node. The<br/>whatToShow flags and the filter, if any, are not<br/>considered when setting this position. The root must not be<br/>null. |
| what_to_show | int | flag specifies which node types may appear in<br/>the logical view of the tree presented by the iterator. See the<br/>description of NodeFilter for the set of possible<br/>SHOW_ values.These flags can be combined using<br/>OR. |
| filter | aspose.html.dom.traversal.INodeFilter | NodeFilter to be used with this<br/>TreeWalker, or null to indicate no filter. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is<br/>null. |





### See Also
* module [`aspose.html.dom`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`INodeIterator`](/html/python-net/aspose.html.dom.traversal/inodeiterator)
