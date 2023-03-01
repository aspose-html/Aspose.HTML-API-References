---
title: Class SVGPathSeg
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Svg.Paths.SVGPathSeg فصل. واجهة SVGPathSeg هي واجهة أساسية تتوافق مع أمر واحد ضمن مواصفات بيانات المسار.
type: docs
weight: 1690
url: /ar/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

واجهة SVGPathSeg هي واجهة أساسية تتوافق مع أمر واحد ضمن مواصفات بيانات المسار.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) { get; } | نوع مقطع المسار كما هو محدد بواسطة أحد الثوابت المحددة في هذه الواجهة . |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | نوع مقطع المسار المحدد بواسطة اسم الأمر المقابل المكون من حرف واحد. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | الإصدارات غير المُدارة و- اختياريًا- الموارد المُدارة. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |

## مجالات

| اسم | وصف |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | يتوافق مع أمر بيانات المسار "arcto المطلق" (A). |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | يتوافق مع أمر "arcto النسبي" (أ) بيانات المسار. |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | يتطابق مع أمر بيانات المسار "closeepath" (z) . |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | يتوافق مع أمر بيانات المسار "مكعب بيزير منحني مطلق" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | يتوافق مع أمر "منحني بيزير نسبي مكعب" (ج) بيانات المسار. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | يتوافق مع أمر بيانات المسار "منحني مكعب سلس مطلق" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | يتوافق مع أمر بيانات المسار "منحني مكعب سلس نسبيًا". |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | يتوافق مع أمر بيانات المسار "منحني بيزير من الدرجة الثانية المطلق" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | يتوافق مع أمر "منحنيات بيزير من الدرجة الثانية" (q) مسار بيانات. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | يتوافق مع أمر بيانات المسار "منحني تربيعي سلس مطلق" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | يتطابق مع أمر "انحناء تربيعي سلس نسبي" (t) أمر بيانات المسار. |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | يتوافق مع أمر بيانات المسار "الخط المطلق" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | يتوافق مع أمر بيانات المسار "خط أفقي مطلق" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | يتوافق مع أمر "خط أفقي نسبي" (h) بيانات المسار. |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | يتوافق مع أمر بيانات المسار "الخط النسبي" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | يتوافق مع أمر بيانات المسار "الخط العمودي المطلق" (V) . |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | يتوافق مع "خط عمودي نسبي" (v) أمر بيانات المسار. |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | يتوافق مع أمر بيانات المسار "moveto" (M) مطلق. |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | يتطابق مع أمر بيانات المسار "النسبي moveto" (m) . |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | نوع الوحدة ليس من الأنواع المحددة مسبقًا. من غير الصحيح محاولة تحديد قيمة جديدة من هذا النوع أو محاولة تبديل قيمة موجودة إلى هذا النوع. |

### أنظر أيضا

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* مساحة الاسم [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* المجسم [Aspose.HTML](../../)


