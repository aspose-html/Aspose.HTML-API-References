---
title: "HTMLTableElement.DeleteRow"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة HTMLTableElement. حذف صف من الجدول"
type: docs

url: /ar/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

حذف صف جدول.

```java
public void DeleteRow(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | Int32 | فهرس الصف الذي سيتم حذفه. يبدأ هذا الفهرس من 0 وهو نسبي للترتيب المنطقي (ليس ترتيب المستند) لجميع الصفوف الموجودة داخل الجدول. إذا كان الفهرس -1 يتم حذف الصف الأخير في الجدول. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: يُثار إذا كان الفهرس المحدد أكبر من أو يساوي عدد الصفوف أو إذا كان الفهرس رقمًا سالبًا غير -1. @version DOM Level 2 |

### انظر أيضًا

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
