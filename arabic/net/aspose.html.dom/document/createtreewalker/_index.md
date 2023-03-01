---
title: Document.CreateTreeWalker
second_title: Aspose.HTML لمرجع .NET API
description: Document طريقة. قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة.
type: docs
weight: 940
url: /ar/net/aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| root | Node | العقدة التي ستعمل كجذر لـ the TreeWalker. لا تؤخذ إشارات whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة ؛ سيتم قبول أي نوع عقدة كجذر. تم تهيئة العقدة الحالية لـ TreeWalker إلى هذه العقدة ، سواء كانت مرئية أم لا. يعمل the root كنقطة توقف لطرق traversal التي تنظر إلى الأعلى في بنية المستند ، مثل parentNode و nextNode. يجب ألا يكون الجذر فارغًا. |

### قيمة الإرجاع

برنامج TreeWalker الذي تم إنشاؤه حديثًا .

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد هو فارغًا. |

### أنظر أيضا

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* مساحة الاسم [Aspose.Html.Dom](../../document/)
* المجسم [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| root | Node | العقدة التي ستعمل كجذر لـ the TreeWalker. لا تؤخذ إشارات whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة ؛ سيتم قبول أي نوع عقدة كجذر. تم تهيئة العقدة الحالية لـ TreeWalker إلى هذه العقدة ، سواء كانت مرئية أم لا. يعمل the root كنقطة توقف لطرق traversal التي تنظر إلى الأعلى في بنية المستند ، مثل parentNode و nextNode. يجب ألا يكون الجذر فارغًا. |
| whatToShow | Int64 | تحدد العلامة أنواع العقدة التي قد تظهر في العرض المنطقي للشجرة الذي يقدمه ممر الشجرة. راجع وصف لـ NodeFilter لمجموعة من القيم الممكنة SHOW_ يمكن دمج هذه العلامات باستخدام OR. |

### قيمة الإرجاع

برنامج TreeWalker الذي تم إنشاؤه حديثًا .

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد هو فارغًا. |

### أنظر أيضا

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* مساحة الاسم [Aspose.Html.Dom](../../document/)
* المجسم [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| root | Node | العقدة التي ستعمل كجذر لـ the TreeWalker. لا تؤخذ إشارات whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة ؛ سيتم قبول أي نوع عقدة كجذر. تم تهيئة العقدة الحالية لـ TreeWalker إلى هذه العقدة ، سواء كانت مرئية أم لا. يعمل the root كنقطة توقف لطرق traversal التي تنظر إلى الأعلى في بنية المستند ، مثل parentNode و nextNode. يجب ألا يكون الجذر فارغًا. |
| whatToShow | Int64 | تحدد العلامة أنواع العقدة التي قد تظهر في العرض المنطقي للشجرة الذي يقدمه ممر الشجرة. راجع وصف لـ NodeFilter لمجموعة من القيم الممكنة SHOW_ يمكن دمج هذه العلامات باستخدام OR. |
| filter | INodeFilter | NodeFilter للاستخدام مع this TreeWalker ، أو null للإشارة إلى عدم وجود عامل تصفية. |

### قيمة الإرجاع

برنامج TreeWalker الذي تم إنشاؤه حديثًا .

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُثار إذا كان الجذر المحدد هو فارغًا. |

### أنظر أيضا

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* مساحة الاسم [Aspose.Html.Dom](../../document/)
* المجسم [Aspose.HTML](../../../)


