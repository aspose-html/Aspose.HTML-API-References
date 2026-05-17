---
title: "Document.CreateNodeIterator"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة عند العقدة المحددة"
type: docs

url: /ar/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي سيتم تكرارها مع أبنائها. يبدأ المؤشر في البداية قبل هذه العقدة مباشرة. لا تُؤخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند تعيين هذا الموضع. يجب ألا تكون الجذر null. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي سيتم تكرارها مع أبنائها. يبدأ المؤشر في البداية قبل هذه العقدة مباشرة. لا تُؤخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند تعيين هذا الموضع. يجب ألا تكون الجذر null. |
| whatToShow | Int64 | العلم يحدد أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها المؤشر. راجع وصف NodeFilter للحصول على مجموعة القيم المحتملة SHOW_. يمكن دمج هذه العلامات باستخدام OR. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي سيتم تكرارها مع أبنائها. يبدأ المؤشر في البداية قبل هذه العقدة مباشرة. لا تُؤخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند تعيين هذا الموضع. يجب ألا تكون الجذر null. |
| whatToShow | Int64 | العلم يحدد أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها المؤشر. راجع وصف NodeFilter للحصول على مجموعة القيم المحتملة SHOW_. يمكن دمج هذه العلامات باستخدام OR. |
| مرشح | INodeFilter | NodeFilter لاستخدامه مع هذا TreeWalker، أو null للدلالة على عدم وجود مرشح. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
