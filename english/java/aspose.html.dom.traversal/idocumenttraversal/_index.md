---
title: IDocumentTraversal Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.traversal.IDocumentTraversal interface. DocumentTraversal contains methods that create iterators and tree-walkers to traverse a node and its children in document order depth first pre-order traversal which is equivalent to the order in which the start tags occur in the text representation of the document. In DOMs which support the Traversal feature DocumentTraversal will be implemented by the same objects that implement the Document interface
type: docs

url: /java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal contains methods that create iterators and tree-walkers to traverse a node and its children in document order (depth first, pre-order traversal, which is equivalent to the order in which the start tags occur in the text representation of the document). In DOMs which support the Traversal feature, DocumentTraversal will be implemented by the same objects that implement the Document interface.

See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Methods

| Name | Description |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Create a new TreeWalker over the subtree rooted at the specified node. |

### See Also

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
