---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML for Java API Reference
description: ITreeWalker property. The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalkers associated filter. currentNode may also be explicitly set to any node whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view by applying the filters in the requested direction if no traversal is possible currentNode is not changed
type: docs
weight: 10
url: /java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed.

```java
public Node CurrentNode { get; set; }
```

### Property Value

The current node.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Raised if an attempt is made to set currentNode to null. |

### See Also

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.Dom.Traversal](../../itreewalker/)
* package [Aspose.HTML](../../../)
