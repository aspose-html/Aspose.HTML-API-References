---
title: "SVGListBase-1.ReplaceItem"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة SVGListBase. تستبدل عنصرًا موجودًا في القائمة بعنصر جديد"
type: docs

url: /ar/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

يستبدل عنصرًا موجودًا في القائمة بعنصر جديد.

```java
public T ReplaceItem(T newItem, ulong index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newItem | T | العنصر الذي سيتم إدراجه في القائمة. |
| index | UInt64 | فهرس العنصر الذي سيتم استبداله. العنصر الأول هو الرقم 0. |

### قيمة الإرجاع

العنصر المُدرج.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). يُرفع عندما لا يمكن تعديل القائمة. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). يُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
