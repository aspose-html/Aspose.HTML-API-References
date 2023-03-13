---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML لمرجع .NET API
description: HTMLTableSectionElement طريقة. أدخل صفًا في هذا القسم. يتم إدخال الصف الجديد مباشرة قبل الحاليفِهرِس الصف العاشر في هذا القسم. إذا فِهرِس هو 1 أو يساوي عدد الصفوف في قسم هذا  يتم إلحاق الصف الجديد.
type: docs
weight: 70
url: /ar/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

أدخل صفًا في هذا القسم. يتم إدخال الصف الجديد مباشرة قبل الحالي`فِهرِس` الصف العاشر في هذا القسم. إذا `فِهرِس` هو -1 أو يساوي عدد الصفوف في قسم هذا ، يتم إلحاق الصف الجديد.

```csharp
public HTMLElement InsertRow(int index)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| index | Int32 | رقم الصف حيث يتم إدراج صف جديد. يبدأ هذا الفهرس من 0 وهو متعلق فقط بالصفوف الموجودة داخل هذا القسم ، وليس كل الصفوف في الجدول. |

### قيمة الإرجاع

الصف الذي تم إنشاؤه حديثًا.

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: يتم رفعه إذا كان الفهرس المحدد أكبر من عدد الصفوف إذا كان الفهرس رقمًا سالبًا بخلاف -1. |

### أنظر أيضا

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* مساحة الاسم [Aspose.Html](../../htmltablesectionelement/)
* المجسم [Aspose.HTML](../../../)


