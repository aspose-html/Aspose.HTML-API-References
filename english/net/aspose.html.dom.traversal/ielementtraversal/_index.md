---
title: IElementTraversal Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Traversal.IElementTraversal interface. The ElementTraversal interface is a set of read-only attributes which allow an author to easily navigate between elements in a document. In conforming implementations of Element Traversal all objects that implement Element must also implement the ElementTraversal interface
type: docs
weight: 2480
url: /net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

The ElementTraversal interface is a set of read-only attributes which allow an author to easily navigate between elements in a document. In conforming implementations of Element Traversal, all objects that implement Element must also implement the ElementTraversal interface.

```csharp
public interface IElementTraversal
```

## Properties

| Name | Description |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |

### See Also

* namespace [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* assembly [Aspose.HTML](../../)
