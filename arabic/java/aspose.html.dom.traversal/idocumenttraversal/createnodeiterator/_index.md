---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة IDocumentTraversal. إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي سيتم تكرارها مع أبنائها. يبدأ المؤشر في البداية مباشرةً قبل هذه العقدة. لا تُؤخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند ضبط هذا الموضع. يجب ألا يكون الجذر null. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي سيتم تكرارها مع أبنائها. يبدأ المؤشر في البداية مباشرةً قبل هذه العقدة. لا تُؤخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند ضبط هذا الموضع. يجب ألا يكون الجذر null. |
| whatToShow | Int64 | العلم يحدد أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها المؤشر. راجع وصف NodeFilter لمجموعة القيم الممكنة SHOW_. يمكن دمج هذه العلامات باستخدام OR. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي سيتم تكرارها مع أبنائها. يبدأ المؤشر في البداية مباشرةً قبل هذه العقدة. لا تُؤخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند ضبط هذا الموضع. يجب ألا يكون الجذر null. |
| whatToShow | Int64 | العلم يحدد أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها المؤشر. راجع وصف NodeFilter لمجموعة القيم الممكنة SHOW_. يمكن دمج هذه العلامات باستخدام OR. |
| مرشح | INodeFilter | NodeFilter لاستخدامه مع هذا TreeWalker، أو null للدلالة على عدم وجود مرشح. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
