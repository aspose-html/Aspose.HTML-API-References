---
title: NodeFilter.AcceptNode
second_title: Aspose.HTML for Java API Reference
description: NodeFilter method. Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator it is not normally called directly from user code. Though you could do so if you wanted to use the same filter to guide your own application logic
type: docs
weight: 10
url: /net/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator; it is not normally called directly from user code. (Though you could do so if you wanted to use the same filter to guide your own application logic.)

```java
public abstract short AcceptNode(Node n)
```

| Parameter | Type | Description |
| --- | --- | --- |
| n | Node | node to check to see if it passes the filter or not. |

### Return Value

a constant to determine whether the node is accepted, rejected, or skipped, as defined above.

### See Also

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.Dom.Traversal.Filters](../../nodefilter/)
* package [Aspose.HTML](../../../)
