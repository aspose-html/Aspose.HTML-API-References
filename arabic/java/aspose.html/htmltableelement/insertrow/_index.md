---
title: "HTMLTableElement.InsertRow"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة HTMLTableElement. أدخل صفًا جديدًا فارغًا في الجدول. يتم إدخال الصف الجديد مباشرةً قبل الصف الحالي في الفهرس نفسه وفي نفس القسم داخل الجدول. إذا كان الفهرس -1 أو يساوي عدد الصفوف، يتم إلحاق الصف الجديد. بالإضافة إلى ذلك، عندما يكون الجدول فارغًا يتم إدخال الصف في TBODY يتم إنشاؤه وإدراجه في الجدول. لا يمكن أن يكون صف الجدول فارغًا وفقًا لـ HTML 4.01"
type: docs

url: /ar/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

إدراج صف جديد فارغ في الجدول. يتم إدراج الصف الجديد مباشرةً قبل الصف الحالي رقم `index` وفي نفس القسم. إذا كان `index` يساوي -1 أو يساوي عدد الصفوف، يتم إلحاق الصف الجديد. بالإضافة إلى ذلك، عندما يكون الجدول فارغًا يتم إدراج الصف في `TBODY` الذي يتم إنشاؤه وإدراجه في الجدول. لا يمكن أن يكون صف الجدول فارغًا وفقًا لـ [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

```java
public Node InsertRow(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | Int32 | رقم الصف حيث يتم إدخال صف جديد. يبدأ هذا الفهرس من 0 وهو نسبي لترتيب المنطق (ليس ترتيب المستند) لجميع الصفوف الموجودة داخل الجدول. |

### قيمة الإرجاع

الصف المُنشأ حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: يُثار إذا كان الفهرس المحدد أكبر من عدد الصفوف أو إذا كان الفهرس رقمًا سالبًا غير -1. @version DOM Level 2 |

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
