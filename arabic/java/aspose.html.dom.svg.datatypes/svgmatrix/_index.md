---
title: "الفئة SVGMatrix"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "الفئة com.aspose.html.dom.svg.datatypes.SVGMatrix. تستخدم العديد من عمليات الرسومات في SVG مصفوفات 2x3 من الشكل a c e b d f والتي عند توسيعها إلى مصفوفة 3x3 لأغراض الحسابات المصفوفية تصبح a c e b d f 0 0 1"
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

تستخدم العديد من عمليات رسومات SVG مصفوفات 2×3 على الشكل: [a c e] [b d f] والتي، عند توسيعها إلى مصفوفة 3×3 لأغراض حساب المصفوفات، تصبح: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | المكوّن A للمصفوفة. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | المكوّن B للمصفوفة. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | المكوّن C للمصفوفة. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | المكوّن D للمصفوفة. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | المكوّن E للمصفوفة. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | المكوّن F للمصفوفة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و - اختياريًا - الموارد المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | يُجري ضرب المصفوفات. تُضرب هذه المصفوفة لاحقًا بمصفوفة أخرى، وتُعيد المصفوفة الجديدة الناتجة. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | يضرب لاحقًا تحويل دوران على المصفوفة الحالية ويعيد المصفوفة الناتجة. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | يضرب لاحقًا تحويل مقياس موحد على المصفوفة الحالية ويعيد المصفوفة الناتجة. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | يضرب لاحقًا تحويل مقياس غير موحد على المصفوفة الحالية ويعيد المصفوفة الناتجة. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | يُضيف عملية تحويل skewX إلى المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | يُضيف عملية تحويل skewY إلى المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | يرجع سلسلة تمثل هذا الكائن. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | يُضيف عملية تحويل ترجمة إلى المصفوفة الحالية ويُعيد المصفوفة الناتجة. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
