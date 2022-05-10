---
title: IDocumentTraversal
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 2580
url: /net/aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal contains methods that create iterators and tree-walkers to traverse a node and its children in document order (depth first, pre-order traversal, which is equivalent to the order in which the start tags occur in the text representation of the document). In DOMs which support the Traversal feature, DocumentTraversal will be implemented by the same objects that implement the Document interface.

See also the [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## Methods

| Name | Description |
| --- | --- |
| [CreateNodeIterator](createnodeiterator)(Node) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNodeIterator](createnodeiterator)(Node, long) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNodeIterator](createnodeiterator)(Node, long, INodeFilter) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateTreeWalker](createtreewalker)(Node) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [CreateTreeWalker](createtreewalker)(Node, long) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [CreateTreeWalker](createtreewalker)(Node, long, INodeFilter) | Create a new TreeWalker over the subtree rooted at the specified node. |

### See Also

* namespace [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->