---
title: create_tree_walker method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 200
url: /aspose.html.dom/document/create_tree_walker/
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
| root | [`Node`](/html/python-net/aspose.html.dom/node) | node which will serve as the root for the<br/>TreeWalker. The whatToShow flags and the<br/>NodeFilter are not considered when setting this value;<br/>any node type will be accepted as the root. The<br/>currentNode of the TreeWalker is<br/>initialized to this node, whether or not it is visible. The<br/>root functions as a stopping point for traversal<br/>methods that look upward in the document structure, such as<br/>parentNode and nextNode. The root must<br/>not be null. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is<br/>null. |




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
| root | [`Node`](/html/python-net/aspose.html.dom/node) | node which will serve as the root for the<br/>TreeWalker. The whatToShow flags and the<br/>NodeFilter are not considered when setting this value;<br/>any node type will be accepted as the root. The<br/>currentNode of the TreeWalker is<br/>initialized to this node, whether or not it is visible. The<br/>root functions as a stopping point for traversal<br/>methods that look upward in the document structure, such as<br/>parentNode and nextNode. The root must<br/>not be null. |
| what_to_show | int | flag specifies which node types may appear in<br/>the logical view of the tree presented by the tree-walker. See the<br/>description of NodeFilter for the set of possible<br/>SHOW_ values.These flags can be combined using OR. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is<br/>null. |




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
| root | [`Node`](/html/python-net/aspose.html.dom/node) | node which will serve as the root for the<br/>TreeWalker. The whatToShow flags and the<br/>NodeFilter are not considered when setting this value;<br/>any node type will be accepted as the root. The<br/>currentNode of the TreeWalker is<br/>initialized to this node, whether or not it is visible. The<br/>root functions as a stopping point for traversal<br/>methods that look upward in the document structure, such as<br/>parentNode and nextNode. The root must<br/>not be null. |
| what_to_show | int | flag specifies which node types may appear in<br/>the logical view of the tree presented by the tree-walker. See the<br/>description of NodeFilter for the set of possible<br/>SHOW_ values.These flags can be combined using OR. |
| filter | aspose.html.dom.traversal.INodeFilter | NodeFilter to be used with this<br/>TreeWalker, or null to indicate no filter. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the specified root is<br/>null. |





### See Also
* module [`aspose.html.dom`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`ITreeWalker`](/html/python-net/aspose.html.dom.traversal/itreewalker)
