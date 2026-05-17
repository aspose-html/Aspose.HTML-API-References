---
title: "SVGListBase-1.InsertItemBefore"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة SVGListBase. تُدرج عنصرًا جديدًا في القائمة في الموضع المحدد. العنصر الأول هو الرقم 0"
type: docs

url: /ar/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

يدرج عنصرًا جديدًا في القائمة في الموضع المحدد. العنصر الأول هو الرقم 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newItem | T | العنصر الذي سيتم إدراجه في القائمة. |
| index | UInt64 | فهرس العنصر الذي سيُدرج قبلّه العنصر الجديد. العنصر الأول هو الرقم 0. إذا كان الفهرس يساوي 0، يتم إدراج العنصر الجديد في مقدمة القائمة. إذا كان الفهرس أكبر من أو يساوي numberOfItems، يتم إلحاق العنصر الجديد بنهاية القائمة. |

### قيمة الإرجاع

العنصر المُدرج.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). يُرفع عندما لا يمكن تعديل القائمة. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
