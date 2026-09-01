---
title: "واجهة IDocumentCSS"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.dom.css.IDocumentCSS. تمثل هذه الواجهة مستندًا مع عرض CSS."
type: docs

url: /ar/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

هذه الواجهة تمثل مستندًا مع عرض CSS.

توفر طريقة getOverrideStyle آلية يمكن من خلالها للمؤلف DOM إحداث تغيير فوري في نمط عنصر دون تعديل أوراق الأنماط المرتبطة صراحةً بالمستند أو النمط المضمن للعناصر في أوراق الأنماط. تأتي ورقة الأنماط هذه بعد ورقة أنماط المؤلف في خوارزمية السلسلة وتُسمى ورقة أنماط التجاوز. تتفوق ورقة أنماط التجاوز على أوراق أنماط المؤلف. لا يزال تصريح \"!important\" يتفوق على تصريح عادي. قد تحتوي أوراق أنماط التجاوز، والمؤلف، والمستخدم جميعها على تصريحات \"!important\". قواعد المستخدم \"!important\" تتفوق على كل من قواعد التجاوز وقواعد المؤلف \"!important\"، وقواعد التجاوز \"!important\" تتفوق على قواعد المؤلف \"!important\".

من المتوقع أنه يمكن الحصول على مثيل من واجهة DocumentCSS باستخدام طرق التحويل الخاصة بالربط على مثيل من واجهة Document.

انظر أيضًا [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | تُستخدم هذه الطريقة لاسترجاع إعلان نمط التجاوز لعنصر محدد وعنصر شبه محدد محدد. |

### انظر أيضًا

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
