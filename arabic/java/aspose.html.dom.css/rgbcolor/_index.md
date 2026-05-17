---
title: "فئة RGBColor"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.css.RGBColor. تُستخدم واجهة RGBColor لتمثيل أي قيمة لون RGB. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. وبالتالي فإن التعديلات التي تُجرى على كائنات CSSPrimitiveValue تُعدل خاصية النمط."
type: docs

url: /ar/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

تُستخدم واجهة RGBColor لتمثيل أي قيمة لون RGB. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. وبالتالي، التعديلات التي تُجرى على كائنات CSSPrimitiveValue تُعدّل خاصية النمط.

لون RGB المحدد لا يتم قصه (حتى إذا كان الرقم خارج النطاق 0-255 أو 0%-100%). يتم قص لون RGB المحسوب حسب الجهاز.

حتى إذا كان ورقة الأنماط يمكنها احتواء عدد صحيح فقط لقيمة اللون، فإن التخزين الداخلي لهذا العدد هو عدد عائم، ويمكن استخدامه كعدد عائم في النمط المحدد أو المحسوب.

يمكن دائمًا تحويل قيمة النسبة المئوية للون إلى رقم والعكس بالعكس.

```java
public class RGBColor : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) يحصل على قيمة مكون ألفا لهذا هيكل Color. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) يحصل على قيمة مكون الأزرق لهذا هيكل Color. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) يحصل على قيمة مكون الأخضر لهذا هيكل Color. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) يحصل على قيمة مكون الأحمر لهذا هيكل Color. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | يحول إلى كائن اللون الأصلي. |

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
