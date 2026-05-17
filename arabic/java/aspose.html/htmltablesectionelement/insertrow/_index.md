---
title: "HTMLTableSectionElement.InsertRow"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة HTMLTableSectionElement. إدراج صف في هذا القسم. يتم إدراج الصف الجديد مباشرةً قبل الصف الحالي رقم الفهرس في هذا القسم. إذا كان الفهرس -1 أو يساوي عدد الصفوف في هذا القسم يتم إلحاق الصف الجديد."
type: docs

url: /ar/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

أدرج صفاً في هذا القسم. يتم إدراج الصف الجديد مباشرةً قبل الصف الحالي رقم `index` في هذا القسم. إذا كان `index` يساوي -1 أو يساوي عدد الصفوف في هذا القسم، يتم إلحاق الصف الجديد.

```java
public HTMLElement InsertRow(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | Int32 | رقم الصف حيث يتم إدراج صف جديد. يبدأ هذا الفهرس من 0 وهو نسبي فقط للصفوف الموجودة داخل هذا القسم، وليس لجميع الصفوف في الجدول. |

### قيمة الإرجاع

الصف المُنشأ حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: يُرفع إذا كان الفهرس المحدد أكبر من عدد الصفوف أو إذا كان الفهرس رقمًا سالبًا غير -1. @version DOM Level 2 |

### انظر أيضًا

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
