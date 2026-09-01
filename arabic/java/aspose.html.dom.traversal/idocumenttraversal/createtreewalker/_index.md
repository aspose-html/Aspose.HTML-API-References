---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة IDocumentTraversal. إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي ستعمل كجذر للـ TreeWalker. لا تُؤخذ علامات whatToShow وNodeFilter في الاعتبار عند ضبط هذه القيمة؛ سيتم قبول أي نوع عقدة كجذر. يتم تهيئة currentNode للـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر صعودًا في بنية المستند، مثل parentNode وnextNode. يجب ألا يكون الجذر null. |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### انظر أيضًا

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي ستعمل كجذر للـ TreeWalker. لا تُؤخذ علامات whatToShow وNodeFilter في الاعتبار عند ضبط هذه القيمة؛ سيتم قبول أي نوع عقدة كجذر. يتم تهيئة currentNode للـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر صعودًا في بنية المستند، مثل parentNode وnextNode. يجب ألا يكون الجذر null. |
| whatToShow | Int64 | العلم يحدد أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها المتجول عبر الشجرة. راجع وصف NodeFilter للحصول على مجموعة القيم الممكنة لـ SHOW_. يمكن دمج هذه العلامات باستخدام OR. |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### انظر أيضًا

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي ستعمل كجذر للـ TreeWalker. لا تُؤخذ علامات whatToShow وNodeFilter في الاعتبار عند ضبط هذه القيمة؛ سيتم قبول أي نوع عقدة كجذر. يتم تهيئة currentNode للـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر صعودًا في بنية المستند، مثل parentNode وnextNode. يجب ألا يكون الجذر null. |
| whatToShow | Int64 | العلم يحدد أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها المتجول عبر الشجرة. راجع وصف NodeFilter للحصول على مجموعة القيم الممكنة لـ SHOW_. يمكن دمج هذه العلامات باستخدام OR. |
| مرشح | INodeFilter | NodeFilter لاستخدامه مع هذا TreeWalker، أو null للدلالة على عدم وجود مرشح. |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### انظر أيضًا

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
