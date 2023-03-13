---
title: SVGListBase1.ReplaceItem
second_title: Aspose.HTML لمرجع .NET API
description: SVGListBase طريقة. استبدال عنصر موجود في القائمة بعنصر جديد.
type: docs
weight: 110
url: /ar/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

استبدال عنصر موجود في القائمة بعنصر جديد.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newItem | T | العنصر الذي سيتم إدراجه في القائمة. |
| index | UInt64 | فهرس العنصر المراد استبداله. العنصر الأول هو رقم 0. |

### قيمة الإرجاع

العنصر المدرج.

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | شفرة[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). تُثار عندما لا يمكن تعديل القائمة. |
| [DOMException](../../../aspose.html.dom/domexception/) | شفرة[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). تُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### أنظر أيضا

* class [SVGListBase&lt;T&gt;](../)
* مساحة الاسم [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* المجسم [Aspose.HTML](../../../)


