---
title: INodeFilter Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.traversal.INodeFilter interface. Filters are objects that know how to filter out nodes. If a NodeIterator or TreeWalker is given a NodeFilter it applies the filter before it returns the next node. If the filter says to accept the node the traversal logic returns it otherwise traversal looks for the next node and pretends that the node that was rejected was not there
type: docs

url: /java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filters are objects that know how to "filter out" nodes. If a NodeIterator or TreeWalker is given a NodeFilter, it applies the filter before it returns the next node. If the filter says to accept the node, the traversal logic returns it; otherwise, traversal looks for the next node and pretends that the node that was rejected was not there.

The DOM does not provide any filters. NodeFilter is just an interface that users can implement to provide their own filters.

NodeFilters do not need to know how to traverse from node to node, nor do they need to know anything about the data structure that is being traversed. This makes it very easy to write filters, since the only thing they have to know how to do is evaluate a single node. One filter may be used with a number of different kinds of traversals, encouraging code reuse.

See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## Methods

| Name | Description |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator; it is not normally called directly from user code. (Though you could do so if you wanted to use the same filter to guide your own application logic.) |

### See Also

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
