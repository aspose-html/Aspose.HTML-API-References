---
title: "فئة SVGTransform"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.dom.svg.datatypes.SVGTransform. SVGTransform هي الواجهة لإحدى التحويلات المكوّنة داخل SVGTransformList، وبالتالي فإن كائن SVGTransform يتوافق مع مكوّن واحد مثل المقياس أو المصفوفة داخل تعريف سمة التحويل."
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform هي الواجهة لإحدى التحويلات المكوّنة داخل SVGTransformList؛ وبالتالي، يطابق كائن SVGTransform مكوّنًا واحدًا (مثل 'scale(…)' أو 'matrix(…)') داخل تعريف سمة ‘transform’.

```java
public class SVGTransform : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) سمة ملائمة لـ SVG_TRANSFORM_ROTATE و SVG_TRANSFORM_SKEWX و SVG_TRANSFORM_SKEWY. تحتفظ بالزاوية المحددة. بالنسبة لـ SVG_TRANSFORM_MATRIX و SVG_TRANSFORM_TRANSLATE و SVG_TRANSFORM_SCALE، ستكون الزاوية صفرًا. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) المصفوفة التي تمثل هذا التحويل. كائن المصفوفة حي، أي أن أي تغييرات تُجرى على كائن SVGTransform تُنعكس فورًا على كائن المصفوفة والعكس بالعكس. في حال تم تعديل كائن المصفوفة مباشرةً (أي دون استخدام الطرق على واجهة SVGTransform نفسها) فإن نوع SVGTransform يتغيّر إلى SVG_TRANSFORM_MATRIX. بالنسبة لـ SVG_TRANSFORM_MATRIX، تحتوي المصفوفة على القيم a, b, c, d, e, f التي يزودها المستخدم. بالنسبة لـ SVG_TRANSFORM_TRANSLATE، تمثل e و f قيم الترجمة (a=1, b=0, c=0, d=1). بالنسبة لـ SVG_TRANSFORM_SCALE، تمثل a و d قيم المقياس (b=0, c=0, e=0, f=0). بالنسبة لـ SVG_TRANSFORM_SKEWX و SVG_TRANSFORM_SKEWY، تمثل a, b, c, d المصفوفة التي ستنتج الانحراف المحدد (e=0 و f=0). بالنسبة لـ SVG_TRANSFORM_ROTATE، تمثل a, b, c, d, e, f معًا المصفوفة التي ستنتج الدوران المحدد. عندما يكون الدوران حول نقطة المركز (0, 0)، تكون e و f صفرًا. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) نوع القيمة كما هو محدد بأحد ثوابت SVG_TRANSFORM_* المعرفة على هذه الواجهة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة - واختياريًا - المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | يضبط نوع التحويل إلى SVG_TRANSFORM_MATRIX، مع المعامل matrix الذي يحدد التحويل الجديد. تُنسخ القيم من معامل matrix، ولا يستبدل معامل matrix الخاص بـ SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | يضبط نوع التحويل إلى SVG_TRANSFORM_ROTATE، مع المعامل angle الذي يحدد زاوية الدوران والمعاملين cx و cy اللذين يحددان مركز الدوران الاختياري. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | يضبط نوع التحويل إلى SVG_TRANSFORM_SCALE، مع المعاملين sx و sy اللذين يحددان قيم المقياس. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | يضبط نوع التحويل إلى SVG_TRANSFORM_SKEWX، مع المعامل angle الذي يحدد مقدار الانحراف. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | يضبط نوع التحويل إلى SVG_TRANSFORM_SKEWY، مع المعامل angle الذي يحدد مقدار الانحراف. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | يضبط نوع التحويل إلى SVG_TRANSFORM_TRANSLATE، مع المعاملين tx و ty اللذين يحددان قيم الترجمة. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | يعيد سلسلة تمثل هذا الكائن. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | تحويل 'matrix(…)' |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | تحويل 'rotate(…)' |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | تحويل 'scale(…)' |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | تحويل 'skewX(…)' |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | تحويل 'skewY(…)' |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | تحويل 'translate(…)' |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | نوع الوحدة ليس أحد الأنواع المعرفة مسبقًا. من غير الصالح محاولة تعريف قيمة جديدة لهذا النوع أو محاولة تحويل قيمة موجودة إلى هذا النوع. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
