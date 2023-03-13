---
title: SVGListBase1.RemoveItem
second_title: Aspose.HTML لمرجع .NET API
description: SVGListBase طريقة. يزيل عنصرًا موجودًا من القائمة .
type: docs
weight: 100
url: /ar/net/aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

يزيل عنصرًا موجودًا من القائمة .

```csharp
public T RemoveItem(ulong index)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| index | UInt64 | فهرس العنصر المراد إزالته. العنصر الأول هو رقم 0. |

### قيمة الإرجاع

العنصر الذي تمت إزالته.

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | شفرة[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). تُثار عندما لا يمكن تعديل القائمة. |
| [DOMException](../../../aspose.html.dom/domexception/) | شفرة[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). تُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### أنظر أيضا

* class [SVGListBase&lt;T&gt;](../)
* مساحة الاسم [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* المجسم [Aspose.HTML](../../../)


