---
title: ITraversal class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/aspose.html.dom.traversal/itraversal/
is_root: false
---

## ITraversal class

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



The ITraversal type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [root](/html/python-net/aspose.html.dom.traversal/itraversal/root) | The root node of the NodeIterator, as specified when it<br/>was created. |
| [what_to_show](/html/python-net/aspose.html.dom.traversal/itraversal/what_to_show) | This attribute determines which node types are presented via the<br/>iterator. The available set of constants is defined in the<br/>NodeFilter interface.  Nodes not accepted by<br/>whatToShow will be skipped, but their children may still<br/>be considered. Note that this skip takes precedence over the filter,<br/>if any. |
| [filter](/html/python-net/aspose.html.dom.traversal/itraversal/filter) | The NodeFilter used to screen nodes. |



### See Also
* module [`aspose.html.dom.traversal`](..)
