---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة HTMLTableSectionElement. حذف صف من هذا القسم"
type: docs

url: /ar/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

احذف صفًا من هذا القسم.

```java
public void DeleteRow(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | Int32 | فهرس الصف المراد حذفه، أو -1 لحذف الصف الأخير. يبدأ هذا الفهرس من 0 وهو نسبي فقط للصفوف الموجودة داخل هذا القسم، وليس لجميع الصفوف في الجدول. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: يُثار إذا كان الفهرس المحدد أكبر من أو يساوي عدد الصفوف أو إذا كان الفهرس رقمًا سالبًا غير -1. @version DOM Level 2 |

### انظر أيضًا

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
