---
title: "فئة SVGMatrix"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.dom.svg.datatypes.SVGMatrix. تستخدم العديد من عمليات الرسومات في SVG مصفوفات 2x3 بالشكل a c e b d f والتي عند توسيعها إلى مصفوفة 3x3 لأغراض حساب المصفوفات تصبح a c e b d f 0 0 1"
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

تستخدم العديد من عمليات الرسومات في SVG مصفوفات 2x3 بالشكل: [a c e] [b d f] والتي، عند توسيعها إلى مصفوفة 3x3 لأغراض حساب المصفوفات، تصبح: [a c e] [b d f] [0 0 1]

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
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة - واختياريًا - المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | ينفّذ ضرب المصفوفات. تُضرب هذه المصفوفة لاحقًا بمصفوفة أخرى، وتُعيد المصفوفة الجديدة الناتجة. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | يضرب لاحقًا تحويل دوران على المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | يضرب لاحقًا تحويل مقياس موحد على المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | يضرب لاحقًا تحويل مقياس غير موحد على المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | يُجري عملية ضرب لاحق لتحويل skewX على المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | يُجري عملية ضرب لاحق لتحويل skewY على المصفوفة الحالية ويُعيد المصفوفة الناتجة. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | يعيد سلسلة تمثل هذا الكائن. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | يُجري عملية ضرب لاحق لتحويل إزاحة على المصفوفة الحالية ويُعيد المصفوفة الناتجة. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
