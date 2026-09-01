---
title: "SVGPathSeg الفئة"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg الفئة. الواجهة SVGPathSeg هي واجهة أساسية تمثل أمرًا واحدًا داخل مواصفة بيانات المسار"
type: docs

url: /ar/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

واجهة SVGPathSeg هي واجهة أساسية تتطابق مع أمر واحد داخل مواصفات بيانات المسار.

```java
public abstract class SVGPathSeg : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) نوع مقطع المسار كما هو محدد بأحد الثوابت المعرفة في هذه الواجهة. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) نوع مقطع المسار، محدد باسم الأمر المكوّن من حرف واحد المقابل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة - واختياريًا - المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | يمثل أمر بيانات مسار \"arcto مطلق\" (A). |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | يمثل أمر بيانات مسار \"arcto نسبي\" (a). |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | يمثل أمر بيانات مسار \"closepath\" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | يمثل أمر بيانات مسار \"منحنى بيزيه مكعب مطلق\" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | يمثل أمر بيانات مسار \"منحنى بيزيه مكعب نسبي\" (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | يمثل أمر بيانات مسار \"منحنى مكعب أملس مطلق\" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | يمثل أمر بيانات مسار \"منحنى مكعب أملس نسبي\" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | يمثل أمر بيانات مسار \"منحنى بيزيه تربيعي مطلق\" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | يمثل أمر بيانات مسار \"منحنى بيزيه تربيعي نسبي\" (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | يمثل أمر بيانات مسار \"منحنى تربيعي أملس مطلق\" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | يتطابق مع أمر بيانات مسار "relative smooth quadratic curveto" (t). |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | يتطابق مع أمر بيانات مسار "absolute lineto" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | يتطابق مع أمر بيانات مسار "absolute horizontal lineto" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | يتطابق مع أمر بيانات مسار "relative horizontal lineto" (h). |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | يتطابق مع أمر بيانات مسار "relative lineto" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | يتطابق مع أمر بيانات مسار "absolute vertical lineto" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | يتطابق مع أمر بيانات مسار "relative vertical lineto" (v). |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | يتطابق مع أمر بيانات مسار "absolute moveto" (M). |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | يتطابق مع أمر بيانات مسار "relative moveto" (m). |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | نوع الوحدة ليس أحد الأنواع المعرفة مسبقًا. من غير الصالح محاولة تعريف قيمة جديدة لهذا النوع أو محاولة تحويل قيمة موجودة إلى هذا النوع. |

### انظر أيضًا

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
