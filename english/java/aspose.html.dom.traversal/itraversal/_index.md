---
title: ITraversal Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Traversal.ITraversal interface. Iterators are used to step through a set of nodes e.g. the set of nodes in a NodeList the document subtree governed by a particular Node the results of a query or any other set of nodes. The set of nodes to be iterated is determined by the implementation of the NodeIterator. DOM Level 2 specifies a single NodeIterator implementation for document-order traversal of a document subtree. Instances of these iterators are created by calling DocumentTraversal .createNodeIterator
type: docs
weight: 2520
url: /java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iterators are used to step through a set of nodes, e.g. the set of nodes in a NodeList, the document subtree governed by a particular Node, the results of a query, or any other set of nodes. The set of nodes to be iterated is determined by the implementation of the NodeIterator. DOM Level 2 specifies a single NodeIterator implementation for document-order traversal of a document subtree. Instances of these iterators are created by calling DocumentTraversal .createNodeIterator().

See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) The NodeFilter used to screen nodes. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) The root node of the NodeIterator, as specified when it was created. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) This attribute determines which node types are presented via the iterator. The available set of constants is defined in the NodeFilter interface. Nodes not accepted by whatToShow will be skipped, but their children may still be considered. Note that this skip takes precedence over the filter, if any. |

### See Also

* package [com.aspose.html.Dom.Traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
