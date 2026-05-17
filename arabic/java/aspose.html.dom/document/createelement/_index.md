---
title: "Document.CreateElement"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. في مستند HTML تقوم طريقة document.createElement بإنشاء عنصر HTML المحدد بواسطة tagName أو عنصر HTMLUnknownElement إذا لم يتم التعرف على tagName"
type: docs

url: /ar/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

في مستند HTML، تقوم طريقة document.createElement() بإنشاء عنصر HTML المحدد بواسطة tagName، أو عنصر [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) إذا لم يتم التعرف على tagName.

```java
public Element CreateElement(String localName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| localName | String | سلسلة تحدد نوع العنصر الذي سيتم إنشاؤه. يتم تهيئة nodeName للعنصر المُنشأ بقيمة tagName. لا تستخدم الأسماء المؤهلة (مثل \"html:a\") مع هذه الطريقة. عند الاستدعاء على مستند HTML، تقوم createElement() بتحويل tagName إلى أحرف صغيرة قبل إنشاء العنصر. |

### قيمة الإرجاع

العنصر الجديد [`Element`](../../element/).

## الأمثلة

```java
var element = document.CreateElement(tagName);
```

### انظر أيضًا

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
