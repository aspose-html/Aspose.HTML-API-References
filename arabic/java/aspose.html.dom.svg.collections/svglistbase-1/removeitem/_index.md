---
title: "SVGListBase-1.RemoveItem"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة SVGListBase. تُزيل عنصرًا موجودًا من القائمة"
type: docs

url: /ar/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

يزيل عنصرًا موجودًا من القائمة.

```java
public T RemoveItem(ulong index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | UInt64 | فهرس العنصر الذي سيُزال. العنصر الأول هو الرقم 0. |

### قيمة الإرجاع

العنصر المُزال.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). يُرفع عندما لا يمكن تعديل القائمة. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). يُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
