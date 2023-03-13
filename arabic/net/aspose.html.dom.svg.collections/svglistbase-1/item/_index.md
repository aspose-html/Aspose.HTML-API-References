---
title: SVGListBase1.Item
second_title: Aspose.HTML لمرجع .NET API
description: SVGListBase ملكية. إرجاع عنصر الفهرس في القائمة.
type: docs
weight: 10
url: /ar/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

إرجاع عنصر الفهرس في القائمة.

```csharp
public T this[ulong index] { get; set; }
```

| معامل | وصف |
| --- | --- |
| index | فهرس في القائمة. |

### قيمة الإرجاع

الكائن المخزن في موضع الفهرس في القائمة.

### Property_Value

نوع العنصر المخزن في القائمة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | شفرة[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). يتم رفعه عندما يتعذر تعديل القائمة. |
| [DOMException](../../../aspose.html.dom/domexception/) | شفرة[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). تُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### أنظر أيضا

* class [SVGListBase&lt;T&gt;](../)
* مساحة الاسم [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* المجسم [Aspose.HTML](../../../)


