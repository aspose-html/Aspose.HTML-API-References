---
title: "Document.CreateAttribute"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. تُنشئ طريقة Document.createAttribute عقدة صفة جديدة وتُعيدها. الكائن يُنشئ عقدة تُطبق واجهة Attr. لا يفرض DOM أي قيود على نوع الصفات التي يمكن إضافتها إلى عنصر معين بهذه الطريقة."
type: docs

url: /ar/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

طريقة Document.createAttribute() تُنشئ عقدة صفة جديدة، وتُعيدها. الكائن يُنشئ عقدة تُطبق واجهة [`Attr`](../../attr/). لا يفرض DOM أي قيود على نوع الصفات التي يمكن إضافتها إلى عنصر معين بهذه الطريقة.

```java
public Attr CreateAttribute(String localName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| localName | String | name هو String يحتوي على اسم الصفة. |

### قيمة الإرجاع

عقدة [`Attr`](../../attr/).

## الأمثلة

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### انظر أيضًا

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
