---
title: Class SVGAngle
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Svg.DataTypes.SVGAngle فصل. تتوافق واجهة SVGAngle مع نوع البيانات الأساسي للزاوية.
type: docs
weight: 1060
url: /ar/net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

تتوافق واجهة SVGAngle مع نوع البيانات الأساسي للزاوية.

```csharp
public class SVGAngle : SVGValueType
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svgangle/unittype/) { get; } | نوع القيمة كما هو محدد بواسطة أحد ثوابت SVG_ANGLETYPE_ * المحددة في هذه الواجهة. |
| [Value](../../aspose.html.dom.svg.datatypes/svgangle/value/) { get; set; } | قيمة الزاوية كقيمة فاصلة عائمة بالدرجات. سيؤدي تعيين هذه السمة إلى تحديث valueInSpecifiedUnits و valueAsString تلقائيًا لتعكس هذا الإعداد. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svgangle/valueasstring/) { get; set; } | قيمة الزاوية كقيمة سلسلة ، بالوحدات التي يتم التعبير عنها بواسطة نوع الوحدة. سيؤدي تعيين هذه السمة إلى تحديث القيمة و valueInSpecifiedUnits و unitType تلقائيًا لتعكس هذا الإعداد. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | قيمة الزاوية كقيمة فاصلة عائمة بالوحدات التي يتم التعبير عنها بواسطة نوع الوحدة. سيؤدي تعيين هذه السمة إلى تحديث القيمة والقيمة AsString تلقائيًا لتعكس هذا الإعداد. |

## طُرق

| اسم | وصف |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | احتفظ بنفس القيمة المخزنة الأساسية ، لكن أعد تعيين معرف الوحدة المخزنة إلى نوع الوحدة المحدد. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString كنتيجة لهذه الطريقة. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | الإصدارات غير المُدارة و- اختياريًا- الموارد المُدارة. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | إعادة تعيين القيمة كرقم مع نوع الوحدة المرتبط ، وبالتالي استبدال القيم لجميع السمات الموجودة على الكائن. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgangle/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | تم ضبط نوع الوحدة بشكل صريح على درجات. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | نوع الوحدة راديان . |
| const [SVG_ANGLETYPE_RAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | نوع الوحدة راديان . |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | نوع الوحدة ليس أحد أنواع الوحدات المحددة مسبقًا. من غير الصحيح محاولة تحديد قيمة جديدة من هذا النوع أو محاولة تبديل قيمة موجودة إلى هذا النوع. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | لم يتم توفير نوع وحدة (على سبيل المثال ، تم تحديد قيمة بدون وحدة). بالنسبة للزوايا ، يتم التعامل مع القيمة بدون وحدة كما لو تم تحديد الدرجات. |

### أنظر أيضا

* class [SVGValueType](../svgvaluetype/)
* مساحة الاسم [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* المجسم [Aspose.HTML](../../)


