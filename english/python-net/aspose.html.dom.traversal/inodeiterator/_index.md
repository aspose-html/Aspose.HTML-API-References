---
title: INodeIterator class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.html.dom.traversal/inodeiterator/
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
| [pointer_before_reference_node](/html/python-net/aspose.html.dom.traversal/inodeiterator/pointer_before_reference_node) | The value of this flag determines whether the children of entity<br/>reference nodes are visible to the iterator. If false, they  and<br/>their descendants will be rejected. Note that this rejection takes<br/>precedence over whatToShow and the filter. Also note<br/>that this is currently the only situation where<br/>NodeIterators may reject a complete subtree rather than<br/>skipping individual nodes.<br/>To produce a view of the document that has entity references<br/>expanded and does not expose the entity reference node itself, use<br/>the whatToShow flags to hide the entity reference node<br/>and set expandEntityReferences to true when creating the<br/>iterator. To produce a view of the document that has entity reference<br/>nodes but no entity expansion, use the whatToShow flags<br/>to show the entity reference node and set<br/>expandEntityReferences to false. |
| [root](/html/python-net/aspose.html.dom.traversal/inodeiterator/root) | The root node of the NodeIterator, as specified when it<br/>was created. |
| [what_to_show](/html/python-net/aspose.html.dom.traversal/inodeiterator/what_to_show) | This attribute determines which node types are presented via the<br/>iterator. The available set of constants is defined in the<br/>NodeFilter interface.  Nodes not accepted by<br/>whatToShow will be skipped, but their children may still<br/>be considered. Note that this skip takes precedence over the filter,<br/>if any. |
| [filter](/html/python-net/aspose.html.dom.traversal/inodeiterator/filter) | The NodeFilter used to screen nodes. |


### Methods
| Method | Description |
| :- | :- |
| [next_node](/html/python-net/aspose.html.dom.traversal/inodeiterator/next_node/#) | Returns the next node in the set and advances the position of the<br/>iterator in the set. After a NodeIterator is created,<br/>the first call to nextNode() returns the first node in<br/>the set. |
| [previous_node](/html/python-net/aspose.html.dom.traversal/inodeiterator/previous_node/#) | Returns the previous node in the set and moves the position of the<br/>NodeIterator backwards in the set. |
| [detach](/html/python-net/aspose.html.dom.traversal/inodeiterator/detach/#) | Detaches the NodeIterator from the set which it iterated<br/>over, releasing any computational resources and placing the iterator<br/>in the INVALID state. After detach has been invoked,<br/>calls to nextNode or previousNode will<br/>raise the exception INVALID_STATE_ERR. |



### See Also
* module [`aspose.html.dom.traversal`](..)
* class [`ITraversal`](/html/python-net/aspose.html.dom.traversal/itraversal)
