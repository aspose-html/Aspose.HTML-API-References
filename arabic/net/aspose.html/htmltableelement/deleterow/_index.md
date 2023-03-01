---
title: HTMLTableElement.DeleteRow
second_title: Aspose.HTML لمرجع .NET API
description: HTMLTableElement طريقة. حذف صف في الجدول.
type: docs
weight: 190
url: /ar/net/aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

حذف صف في الجدول.

```csharp
public void DeleteRow(int index)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| index | Int32 | فهرس الصف المراد حذفه. يبدأ هذا الفهرس من 0 وهو مرتبط بالترتيب المنطقي (وليس ترتيب المستند) لـ جميع الصفوف الموجودة داخل الجدول. إذا كان الفهرس -1 ، فسيتم حذف الصف الأخير في الجدول. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: يتم رفعه إذا كان الفهرس المحدد أكبر من أو يساوي عدد الصفوف أو إذا كان الفهرس رقمًا سالبًا بخلاف -1. @ الإصدار DOM المستوى 2 |

### أنظر أيضا

* class [HTMLTableElement](../)
* مساحة الاسم [Aspose.Html](../../htmltableelement/)
* المجسم [Aspose.HTML](../../../)


