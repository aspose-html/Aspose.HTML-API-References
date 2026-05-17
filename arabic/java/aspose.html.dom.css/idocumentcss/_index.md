---
title: "واجهة IDocumentCSS"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.css.IDocumentCSS. تمثل هذه الواجهة مستندًا مع عرض CSS."
type: docs

url: /ar/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

هذه الواجهة تمثل مستندًا مع عرض CSS.

توفر طريقة getOverrideStyle آلية يمكن من خلالها لمؤلف DOM إحداث تغيير فوري في نمط عنصر دون تعديل أوراق الأنماط المرتبطة صراحةً بالمستند أو النمط المضمن للعناصر في أوراق الأنماط. تأتي هذه ورقة الأنماط بعد ورقة أنماط المؤلف في خوارزمية السلسلة وتُسمى ورقة أنماط التجاوز (override style sheet). تتفوق ورقة أنماط التجاوز على أوراق أنماط المؤلف. لا يزال إعلان \"!important\" يتفوق على إعلان عادي. يمكن أن تحتوي أوراق أنماط التجاوز، والمؤلف، والمستخدم جميعها على إعلانات \"!important\". تتفوق قواعد المستخدم \"!important\" على كل من قواعد التجاوز والمؤلف \"!important\"، وتتفوق قواعد التجاوز \"!important\" على قواعد المؤلف \"!important\".

من المتوقع أنه يمكن الحصول على مثيل من واجهة DocumentCSS باستخدام طرق التحويل الخاصة بالربط على مثيل من واجهة Document.

انظر أيضًا إلى [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

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
