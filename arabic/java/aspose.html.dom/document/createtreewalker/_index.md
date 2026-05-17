---
title: "Document.CreateTreeWalker"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة المستند. إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة عند العقدة المحددة"
type: docs

url: /ar/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي ستعمل كجذر للـ TreeWalker. لا تُؤخذ علامات whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة؛ سيتم قبول أي نوع من العقد كجذر. يتم تهيئة currentNode للـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر صعودًا في بنية المستند، مثل parentNode و nextNode. يجب ألا يكون الجذر null. |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي ستعمل كجذر للـ TreeWalker. لا تُؤخذ علامات whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة؛ سيتم قبول أي نوع من العقد كجذر. يتم تهيئة currentNode للـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر صعودًا في بنية المستند، مثل parentNode و nextNode. يجب ألا يكون الجذر null. |
| whatToShow | Int64 | تحدد العلامة أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها متصفح الشجرة. راجع وصف NodeFilter للحصول على مجموعة القيم الممكنة لـ SHOW_. يمكن دمج هذه العلامات باستخدام OR. |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| جذر | Node | العقدة التي ستعمل كجذر للـ TreeWalker. لا تُؤخذ علامات whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة؛ سيتم قبول أي نوع من العقد كجذر. يتم تهيئة currentNode للـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر صعودًا في بنية المستند، مثل parentNode و nextNode. يجب ألا يكون الجذر null. |
| whatToShow | Int64 | تحدد العلامة أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها متصفح الشجرة. راجع وصف NodeFilter للحصول على مجموعة القيم الممكنة لـ SHOW_. يمكن دمج هذه العلامات باستخدام OR. |
| مرشح | INodeFilter | NodeFilter لاستخدامه مع هذا TreeWalker، أو null للدلالة على عدم وجود مرشح. |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
