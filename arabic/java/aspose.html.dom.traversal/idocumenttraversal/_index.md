---
title: "واجهة IDocumentTraversal"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.dom.traversal.IDocumentTraversal. يحتوي DocumentTraversal على طرق تُنشئ المتكررات (iterators) و الـ tree-walkers لاستعراض عقدة وأطفالها بترتيب المستند بطريقة عمق‑أول (pre-order) وهو ما يعادل الترتيب الذي تظهر فيه وسوم البداية في تمثيل النص للمستند. في DOMs التي تدعم ميزة Traversal، سيتم تنفيذ DocumentTraversal بواسطة نفس الكائنات التي تُنفّذ واجهة Document."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

يحتوي DocumentTraversal على طرق تُنشئ مُكررات ومُتجوالات شجرة لتصفح عقدة وأطفالها بترتيب المستند (تصفح عمق أولاً، قبل الترتيب المسبق، وهو ما يعادل الترتيب الذي تظهر فيه وسوم البداية في تمثيل النص للمستند). في DOMs التي تدعم ميزة Traversal، سيتم تنفيذ DocumentTraversal بواسطة نفس الكائنات التي تنفذ واجهة Document.

انظر أيضاً إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |

### انظر أيضًا

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
