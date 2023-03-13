---
title: SVGTransform.Matrix
second_title: Aspose.HTML لمرجع .NET API
description: SVGTransform ملكية. المصفوفة التي تمثل هذا التحول. كائن المصفوفة مباشر  مما يعني أن أي تغييرات يتم إجراؤها على كائن SVGTransform تنعكس على الفور في كائن المصفوفة والعكس صحيح. في حالة تغيير كائن المصفوفة مباشرةً أي بدون استخدام الطرق الموجودة على واجهة SVGTransform نفسها  فإن نوع SVGTransform يتغير إلى SVG_TRANSFORM_MATRIX. بالنسبة إلى SVG_TRANSFORM_MATRIX  تحتوي المصفوفة على a  b  c  d  e  f القيم التي يوفرها المستخدم. بالنسبة إلى SVG_TRANSFORM_TRANSLATE  تمثل e و f مقادير الترجمة أ  1  ب  0  ج  0 و د  1 . بالنسبة إلى SVG_TRANSFORM_SCALE  تمثل a و d مقادير الحجم ب  0  c  0 e  0 and f  0 . بالنسبة إلى SVG_TRANSFORM_SKEWX و SVG_TRANSFORM_SKEWY  تمثل a و b و c و d المصفوفة التي ستؤدي إلى الانحراف المحدد e  0 و f  0 . بالنسبة إلى SVG_TRANSFORM_ROTATE تمثل a و b و c و d و e و f معًا المصفوفة التي ستؤدي إلى الدوران المعطى. عندما يكون الدوران حول نقطة المركز 0  0  سيكون e و f صفرًا.
type: docs
weight: 20
url: /ar/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

المصفوفة التي تمثل هذا التحول. كائن المصفوفة مباشر ، مما يعني أن أي تغييرات يتم إجراؤها على كائن SVGTransform تنعكس على الفور في كائن المصفوفة والعكس صحيح. في حالة تغيير كائن المصفوفة مباشرةً (أي بدون استخدام الطرق الموجودة على واجهة SVGTransform نفسها) ، فإن نوع SVGTransform يتغير إلى SVG_TRANSFORM_MATRIX. بالنسبة إلى SVG_TRANSFORM_MATRIX ، تحتوي المصفوفة على a ، b ، c ، d ، e ، f القيم التي يوفرها المستخدم. بالنسبة إلى SVG_TRANSFORM_TRANSLATE ، تمثل e و f مقادير الترجمة (أ = 1 ، ب = 0 ، ج = 0 و د = 1) . بالنسبة إلى SVG_TRANSFORM_SCALE ، تمثل a و d مقادير الحجم (ب = 0 ، c = 0، e = 0 and f = 0) . بالنسبة إلى SVG_TRANSFORM_SKEWX و SVG_TRANSFORM_SKEWY ، تمثل a و b و c و d المصفوفة التي ستؤدي إلى الانحراف المحدد (e = 0 و f = 0) . بالنسبة إلى SVG_TRANSFORM_ROTATE تمثل a و b و c و d و e و f معًا المصفوفة التي ستؤدي إلى الدوران المعطى. عندما يكون الدوران حول نقطة المركز (0 ، 0) ، سيكون e و f صفرًا.

```csharp
public SVGMatrix Matrix { get; }
```

### Property_Value

المصفوفة التي تمثل هذا التحول .

### أنظر أيضا

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* مساحة الاسم [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* المجسم [Aspose.HTML](../../../)


