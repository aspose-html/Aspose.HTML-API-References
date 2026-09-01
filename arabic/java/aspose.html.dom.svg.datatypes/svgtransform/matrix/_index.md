---
title: "SVGTransform.Matrix"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية SVGTransform. المصفوفة التي تمثل هذا التحويل. كائن المصفوفة حي، مما يعني أن أي تغييرات تُجرى على كائن SVGTransform تُنعكس فورًا على كائن المصفوفة والعكس بالعكس. في حال تم تغيير كائن المصفوفة مباشرةً أي بدون استخدام الأساليب على واجهة SVGTransform نفسها، فإن نوع SVGTransform يتغير إلى SVG_TRANSFORM_MATRIX. بالنسبة لـ SVG_TRANSFORM_MATRIX، تحتوي المصفوفة على القيم a b c d e f التي يقدمها المستخدم. بالنسبة لـ SVG_TRANSFORM_TRANSLATE، تمثل e و f مقدار الترجمة (a= 1, b= 0, c= 0 و d = 1). بالنسبة لـ SVG_TRANSFORM_SCALE، تمثل a و d مقدار التكبير (b= 0, c= 0, e= 0 و f = 0). بالنسبة لـ SVG_TRANSFORM_SKEWX و SVG_TRANSFORM_SKEWY، تمثل a b c و d المصفوفة التي ستنتج الانحراف المحدد (e= 0 و f = 0). بالنسبة لـ SVG_TRANSFORM_ROTATE، تمثل a b c d e و f معًا المصفوفة التي ستنتج الدوران المحدد. عندما يكون الدوران حول نقطة المركز (0, 0)، ستكون e و f صفرًا."
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

المصفوفة التي تمثل هذا التحويل. كائن المصفوفة حي، مما يعني أن أي تغييرات تُجرى على كائن SVGTransform تُنعكس فورًا على كائن المصفوفة والعكس بالعكس. في حال تم تغيير كائن المصفوفة مباشرةً (أي بدون استخدام الأساليب على واجهة SVGTransform نفسها) فإن نوع SVGTransform يتغير إلى SVG_TRANSFORM_MATRIX. بالنسبة لـ SVG_TRANSFORM_MATRIX، تحتوي المصفوفة على القيم a, b, c, d, e, f التي يقدمها المستخدم. بالنسبة لـ SVG_TRANSFORM_TRANSLATE، تمثل e و f مقدار الترجمة (a= 1, b= 0, c= 0 و d = 1). بالنسبة لـ SVG_TRANSFORM_SCALE، تمثل a و d مقدار التكبير (b= 0, c= 0, e= 0 و f = 0). بالنسبة لـ SVG_TRANSFORM_SKEWX و SVG_TRANSFORM_SKEWY، تمثل a, b, c و d المصفوفة التي ستنتج الانحراف المحدد (e= 0 و f = 0). بالنسبة لـ SVG_TRANSFORM_ROTATE، تمثل a, b, c, d, e و f معًا المصفوفة التي ستنتج الدوران المحدد.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

المصفوفة التي تمثل هذا التحويل.

### انظر أيضًا

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
