---
title: HTMLTableRowElement.InsertCell
second_title: Aspose.HTML لمرجع .NET API
description: HTMLTableRowElement طريقة. أدخل ملفًا فارغًاTD خلية في هذا الصف. إذا فِهرِس هي 1 أو يساوي عدد الخلايا  يتم إلحاق الخلية الجديدة.
type: docs
weight: 100
url: /ar/net/aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

أدخل ملفًا فارغًا`TD` خلية في هذا الصف. إذا `فِهرِس` هي -1 أو يساوي عدد الخلايا ، يتم إلحاق الخلية الجديدة.

```csharp
public HTMLElement InsertCell(int index)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| index | Int32 | مكان إدراج الخلية ، بدءًا من 0. |

### قيمة الإرجاع

الخلية المنشأة حديثًا.

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: يتم رفعه إذا تم تحديده`فِهرِس` أكبر من عدد الخلايا أو إذا كان الفهرس رقمًا سالبًا آخر من -1. @ الإصدار DOM المستوى 2 |

### أنظر أيضا

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* مساحة الاسم [Aspose.Html](../../htmltablerowelement/)
* المجسم [Aspose.HTML](../../../)


