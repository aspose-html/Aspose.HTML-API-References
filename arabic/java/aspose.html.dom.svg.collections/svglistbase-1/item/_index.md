---
title: "SVGListBase-1.Item"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية SVGListBase. تُرجع العنصر رقم الفهرس في القائمة"
type: docs

url: /ar/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

تُرجع العنصر رقم الفهرس في القائمة.

```java
public T this[ulong index] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| index | الفهرس في القائمة. |

### قيمة الإرجاع

الكائن المخزن في الموضع رقم الفهرس في القائمة.

### Property Value

نوع العنصر المخزن في القائمة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). يُرفع عندما لا يمكن تعديل القائمة. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). يُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
