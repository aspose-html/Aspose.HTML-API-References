---
title: ITreeWalker class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 60
url: /aspose.html.dom.traversal/itreewalker/
is_root: false
---

## ITreeWalker class

TreeWalker objects are used to navigate a document tree or 
subtree using the view of the document defined by their 
whatToShow flags and filter (if any). Any function which 
performs navigation using a TreeWalker will automatically 
support any view defined by a TreeWalker.

Omitting nodes from the logical view of a subtree can result in a 
structure that is substantially different from the same subtree in the 
complete, unfiltered document. Nodes that are siblings in the 
TreeWalker view may be children of different, widely 
separated nodes in the original view. For instance, consider a 
NodeFilter that skips all nodes except for Text nodes and 
the root node of a document. In the logical view that results, all text 
nodes will be siblings and appear as direct children of the root node, no 
matter how deeply nested the structure of the original document.



See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113).
@since DOM Level 2



The ITreeWalker type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [current_node](/html/python-net/aspose.html.dom.traversal/itreewalker/current_node) | The node at which the TreeWalker is currently positioned.<br/>Alterations to the DOM tree may cause the current node to no longer<br/>be accepted by the TreeWalker's associated filter.<br/>currentNode may also be explicitly set to any node,<br/>whether or not it is within the subtree specified by the<br/>root node or would be accepted by the filter and<br/>whatToShow flags. Further traversal occurs relative to<br/>currentNode even if it is not part of the current view,<br/>by applying the filters in the requested direction; if no traversal<br/>is possible, currentNode is not changed. |
| [root](/html/python-net/aspose.html.dom.traversal/itreewalker/root) | The root node of the NodeIterator, as specified when it<br/>was created. |
| [what_to_show](/html/python-net/aspose.html.dom.traversal/itreewalker/what_to_show) | This attribute determines which node types are presented via the<br/>iterator. The available set of constants is defined in the<br/>NodeFilter interface.  Nodes not accepted by<br/>whatToShow will be skipped, but their children may still<br/>be considered. Note that this skip takes precedence over the filter,<br/>if any. |
| [filter](/html/python-net/aspose.html.dom.traversal/itreewalker/filter) | The NodeFilter used to screen nodes. |


### Methods
| Method | Description |
| :- | :- |
| [parent_node](/html/python-net/aspose.html.dom.traversal/itreewalker/parent_node/#) | Moves to and returns the closest visible ancestor node of the current<br/>node. If the search for parentNode attempts to step<br/>upward from the TreeWalker's root node, or<br/>if it fails to find a visible ancestor node, this method retains the<br/>current position and returns null. |
| [first_child](/html/python-net/aspose.html.dom.traversal/itreewalker/first_child/#) | Moves the TreeWalker to the first visible child of the<br/>current node, and returns the new node. If the current node has no<br/>visible children, returns null, and retains the current<br/>node. |
| [last_child](/html/python-net/aspose.html.dom.traversal/itreewalker/last_child/#) | Moves the TreeWalker to the last visible child of the<br/>current node, and returns the new node. If the current node has no<br/>visible children, returns null, and retains the current<br/>node. |
| [previous_sibling](/html/python-net/aspose.html.dom.traversal/itreewalker/previous_sibling/#) | Moves the TreeWalker to the previous sibling of the<br/>current node, and returns the new node. If the current node has no<br/>visible previous sibling, returns null, and retains the<br/>current node. |
| [next_sibling](/html/python-net/aspose.html.dom.traversal/itreewalker/next_sibling/#) | Moves the TreeWalker to the next sibling of the current<br/>node, and returns the new node. If the current node has no visible<br/>next sibling, returns null, and retains the current node. |
| [previous_node](/html/python-net/aspose.html.dom.traversal/itreewalker/previous_node/#) | Moves the TreeWalker to the previous visible node in<br/>document order relative to the current node, and returns the new<br/>node. If the current node has no previous node,  or if the search for<br/>previousNode attempts to step upward from the<br/>TreeWalker's root node,  returns<br/>null, and retains the current node. |
| [next_node](/html/python-net/aspose.html.dom.traversal/itreewalker/next_node/#) | Moves the TreeWalker to the next visible node in document<br/>order relative to the current node, and returns the new node. If the<br/>current node has no next node, or if the search for nextNode attempts<br/>to step upward from the TreeWalker's root<br/>node, returns null, and retains the current node. |



### See Also
* module [`aspose.html.dom.traversal`](..)
* class [`ITraversal`](/html/python-net/aspose.html.dom.traversal/itraversal)
