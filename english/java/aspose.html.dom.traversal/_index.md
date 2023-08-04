---
title: com.aspose.html.dom.Traversal
second_title: Aspose.HTML for Java API Reference
description: The com.aspose.html.Dom.Traversal package contains methods that create iterators and tree-walkers to navigate between elements and traverse a node and its children in document order
type: docs
weight: 180
url: /java/com.aspose.html.dom.traversal/
---
The **com.aspose.html.Dom.Traversal** package contains methods that create iterators and tree-walkers to navigate between elements and traverse a node and its children in document order.

## Interfaces

| Interface | Description |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal contains methods that create iterators and tree-walkers to traverse a node and its children in document order (depth first, pre-order traversal, which is equivalent to the order in which the start tags occur in the text representation of the document). In DOMs which support the Traversal feature, DocumentTraversal will be implemented by the same objects that implement the Document interface. |
| [IElementTraversal](./ielementtraversal/) | The ElementTraversal interface is a set of read-only attributes which allow an author to easily navigate between elements in a document. In conforming implementations of Element Traversal, all objects that implement Element must also implement the ElementTraversal interface. |
| [INodeFilter](./inodefilter/) | Filters are objects that know how to "filter out" nodes. If a NodeIterator or TreeWalker is given a NodeFilter, it applies the filter before it returns the next node. If the filter says to accept the node, the traversal logic returns it; otherwise, traversal looks for the next node and pretends that the node that was rejected was not there. |
| [INodeIterator](./inodeiterator/) | Iterators are used to step through a set of nodes, e.g. the set of nodes in a NodeList, the document subtree governed by a particular Node, the results of a query, or any other set of nodes. The set of nodes to be iterated is determined by the implementation of the NodeIterator. DOM Level 2 specifies a single NodeIterator implementation for document-order traversal of a document subtree. Instances of these iterators are created by calling DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Iterators are used to step through a set of nodes, e.g. the set of nodes in a NodeList, the document subtree governed by a particular Node, the results of a query, or any other set of nodes. The set of nodes to be iterated is determined by the implementation of the NodeIterator. DOM Level 2 specifies a single NodeIterator implementation for document-order traversal of a document subtree. Instances of these iterators are created by calling DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | TreeWalker objects are used to navigate a document tree or subtree using the view of the document defined by their whatToShow flags and filter (if any). Any function which performs navigation using a TreeWalker will automatically support any view defined by a TreeWalker. |
