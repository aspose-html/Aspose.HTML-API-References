---
title: ITreeWalker Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.traversal.ITreeWalker interface. TreeWalker objects are used to navigate a document tree or subtree using the view of the document defined by their whatToShow flags and filter if any. Any function which performs navigation using a TreeWalker will automatically support any view defined by a TreeWalker
type: docs
weight: 2690
url: /java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker objects are used to navigate a document tree or subtree using the view of the document defined by their whatToShow flags and filter (if any). Any function which performs navigation using a TreeWalker will automatically support any view defined by a TreeWalker.

Omitting nodes from the logical view of a subtree can result in a structure that is substantially different from the same subtree in the complete, unfiltered document. Nodes that are siblings in the TreeWalker view may be children of different, widely separated nodes in the original view. For instance, consider a NodeFilter that skips all nodes except for Text nodes and the root node of a document. In the logical view that results, all text nodes will be siblings and appear as direct children of the root node, no matter how deeply nested the structure of the original document.

See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Properties

| Name | Description |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Methods

| Name | Description |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Moves the TreeWalker to the first visible child of the current node, and returns the new node. If the current node has no visible children, returns null, and retains the current node. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Moves the TreeWalker to the last visible child of the current node, and returns the new node. If the current node has no visible children, returns null, and retains the current node. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Moves the TreeWalker to the next visible node in document order relative to the current node, and returns the new node. If the current node has no next node, or if the search for nextNode attempts to step upward from the TreeWalker's root node, returns null, and retains the current node. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Moves the TreeWalker to the next sibling of the current node, and returns the new node. If the current node has no visible next sibling, returns null, and retains the current node. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Moves to and returns the closest visible ancestor node of the current node. If the search for parentNode attempts to step upward from the TreeWalker's root node, or if it fails to find a visible ancestor node, this method retains the current position and returns null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Moves the TreeWalker to the previous visible node in document order relative to the current node, and returns the new node. If the current node has no previous node, or if the search for previousNode attempts to step upward from the TreeWalker's root node, returns null, and retains the current node. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Moves the TreeWalker to the previous sibling of the current node, and returns the new node. If the current node has no visible previous sibling, returns null, and retains the current node. |

### See Also

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
