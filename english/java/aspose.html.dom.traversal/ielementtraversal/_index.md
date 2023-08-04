---
title: IElementTraversal Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Traversal.IElementTraversal interface. The ElementTraversal interface is a set of read-only attributes which allow an author to easily navigate between elements in a document. In conforming implementations of Element Traversal all objects that implement Element must also implement the ElementTraversal interface
type: docs
weight: 2490
url: /java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

The ElementTraversal interface is a set of read-only attributes which allow an author to easily navigate between elements in a document. In conforming implementations of Element Traversal, all objects that implement Element must also implement the ElementTraversal interface.

```java
public interface IElementTraversal
```

## Properties

| Name | Description |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Returns the first child element node of this element. null if this element has no child elements. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Returns the last child element node of this element. null if this element has no child elements. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |

### See Also

* package [com.aspose.html.Dom.Traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
