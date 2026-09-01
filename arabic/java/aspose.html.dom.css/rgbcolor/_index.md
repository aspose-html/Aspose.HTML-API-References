---
title: "فئة RGBColor"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.dom.css.RGBColor. تُستخدم واجهة RGBColor لتمثيل أي قيمة لون RGB. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. وبالتالي فإن التعديلات التي تُجرى على كائنات CSSPrimitiveValue تعدل خاصية النمط."
type: docs

url: /ar/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

تُستخدم واجهة RGBColor لتمثيل أي قيمة لون RGB. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. وبالتالي، التعديلات التي تُجرى على كائنات CSSPrimitiveValue تعدل خاصية النمط.

لون RGB المحدد لا يتم تقطيعه (حتى إذا كان الرقم خارج النطاق 0-255 أو 0%-100%). يتم تقطيع لون RGB المحسوب حسب الجهاز.

حتى إذا كان ورق الأنماط يمكنه احتواء عدد صحيح فقط لقيمة اللون، فإن التخزين الداخلي لهذا العدد هو عدد عشري (float)، ويمكن استخدامه كعدد عشري في النمط المحدد أو المحسوب.

يمكن دائمًا تحويل قيمة النسبة المئوية للون إلى عدد والعكس بالعكس.

```java
public class RGBColor : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) يحصل على قيمة المكوّن ألفا لهذا الهيكل Color. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) يحصل على قيمة المكوّن أزرق لهذا الهيكل Color. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) يحصل على قيمة المكوّن أخضر لهذا الهيكل Color. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) يحصل على قيمة المكوّن أحمر لهذا الهيكل Color. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | يحوّل إلى كائن اللون الأصلي. |

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
