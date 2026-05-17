---
title: "HTMLTableRowElement.InsertCell"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة HTMLTableRowElement. أدخل خلية TD فارغة في هذا الصف. إذا كان index يساوي -1 أو يساوي عدد الخلايا يتم إلحاق الخلية الجديدة"
type: docs

url: /ar/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

أدرج خلية `TD` فارغة في هذا الصف. إذا كان `index` يساوي -1 أو يساوي عدد الخلايا، تُضاف الخلية الجديدة في النهاية.

```java
public HTMLElement InsertCell(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | Int32 | المكان لإدراج الخلية، بدءًا من 0. |

### قيمة الإرجاع

الخلية التي تم إنشاؤها حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: تم رفعه إذا كان `index` المحدد أكبر من عدد الخلايا أو إذا كان `index` رقمًا سالبًا غير -1. @version DOM Level 2 |

### انظر أيضًا

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
