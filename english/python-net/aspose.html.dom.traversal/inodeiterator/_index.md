﻿---
title: INodeIterator class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.html.dom.traversal/inodeiterator/
is_root: false
---

## INodeIterator class

Iterators are used to step through a set of nodes, e.g. the 
set of nodes in a NodeList, the document subtree governed by 
a particular Node, the results of a query, or any other set 
of nodes. The set of nodes to be iterated is determined by the 
implementation of the NodeIterator. DOM Level 2 specifies a 
single NodeIterator implementation for document-order 
traversal of a document subtree. Instances of these iterators are created 
by calling DocumentTraversal
.createNodeIterator().

See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113).
@since DOM Level 2



The INodeIterator type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [reference_node](/html/python-net/aspose.html.dom.traversal/inodeiterator/reference_node) | The current reference node. |
| [pointer_before_reference_node](/html/python-net/aspose.html.dom.traversal/inodeiterator/pointer_before_reference_node) | The value of this flag determines whether the children of entity
| [root](/html/python-net/aspose.html.dom.traversal/inodeiterator/root) | The root node of the NodeIterator, as specified when it
| [what_to_show](/html/python-net/aspose.html.dom.traversal/inodeiterator/what_to_show) | This attribute determines which node types are presented via the
| [filter](/html/python-net/aspose.html.dom.traversal/inodeiterator/filter) | The NodeFilter used to screen nodes. |


### Methods
| Method | Description |
| :- | :- |
| [next_node](/html/python-net/aspose.html.dom.traversal/inodeiterator/next_node/#) | Returns the next node in the set and advances the position of the
| [previous_node](/html/python-net/aspose.html.dom.traversal/inodeiterator/previous_node/#) | Returns the previous node in the set and moves the position of the
| [detach](/html/python-net/aspose.html.dom.traversal/inodeiterator/detach/#) | Detaches the NodeIterator from the set which it iterated



### See Also
* module [`aspose.html.dom.traversal`](..)
* class [`ITraversal`](/html/python-net/aspose.html.dom.traversal/itraversal)