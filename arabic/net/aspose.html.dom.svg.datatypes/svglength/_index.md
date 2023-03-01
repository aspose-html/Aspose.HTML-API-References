---
title: Class SVGLength
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength فصل. تتوافق واجهة SVGLength مع نوع البيانات الأساسي للطول. يمكن تعيين كائن SVGLength للقراءة فقط  مما يعني أن محاولات تعديل الكائن ستؤدي إلى طرح استثناء  كما هو موضح أدناه.
type: docs
weight: 1200
url: /ar/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

تتوافق واجهة SVGLength مع نوع البيانات الأساسي للطول. يمكن تعيين كائن SVGLength للقراءة فقط ، مما يعني أن محاولات تعديل الكائن ستؤدي إلى طرح استثناء ، كما هو موضح أدناه.

```csharp
public class SVGLength : SVGValueType
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | نوع القيمة كما هو محدد بواسطة أحد ثوابت SVG_LENGTHTYPE_ * المحددة في هذه الواجهة . |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | القيمة كقيمة فاصلة عائمة بوحدات المستخدم. سيؤدي تعيين هذه السمة إلى تحديث valueInSpecifiedUnits و valueAsString تلقائيًا لتعكس هذا الإعداد. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | القيمة كقيمة سلسلة ، بالوحدات التي يتم التعبير عنها بواسطة نوع الوحدة. سيؤدي تعيين هذه السمة إلى تحديث القيمة و valueInSpecifiedUnits و unitType تلقائيًا لتعكس هذا الإعداد. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | القيمة كقيمة فاصلة عائمة بالوحدات التي يتم التعبير عنها بواسطة نوع الوحدة. سيؤدي تعيين هذه السمة إلى تحديث القيمة والقيمة AsString تلقائيًا لتعكس هذا الإعداد. |

## طُرق

| اسم | وصف |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | احتفظ بنفس القيمة المخزنة الأساسية ، لكن أعد تعيين معرف الوحدة المخزنة إلى نوع الوحدة المحدد. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString كنتيجة لهذه الطريقة. على سبيل المثال ، إذا كانت القيمة الأصلية "0.5 سم" وتم استدعاء الطريقة للتحويل إلى ملليمترات ، فسيتم تغيير نوع الوحدة إلى SVG_LENGTHTYPE_MM ، وسيتم تغيير valueInSpecifiedUnits إلى القيمة الرقمية 5 وسيتم تغيير القيمة AsString إلى "5mm". |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | الإصدارات غير المُدارة و- اختياريًا- الموارد المُدارة. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | إعادة تعيين القيمة كرقم مع نوع الوحدة المرتبط ، وبالتالي استبدال القيم لجميع السمات الموجودة على الكائن. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | تم تحديد قيمة باستخدام وحدات cm المحددة في CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | تم تحديد قيمة باستخدام وحدات em المحددة في CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | تم تحديد قيمة باستخدام الوحدات السابقة المحددة في CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | تم تحديد قيمة باستخدام الوحدات المحددة في CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | تم تحديد قيمة باستخدام وحدات mm المحددة في CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | لم يتم توفير نوع وحدة (على سبيل المثال ، تم تحديد قيمة بدون وحدة) ، مما يشير إلى قيمة بوحدات المستخدم. |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | تم تحديد قيمة باستخدام وحدات الكمبيوتر المحددة في CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | تم تحديد قيمة النسبة المئوية . |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | تم تحديد قيمة باستخدام وحدات pt المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | تم تحديد قيمة باستخدام وحدات البكسل المحددة في CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | نوع الوحدة ليس أحد أنواع الوحدات المحددة مسبقًا. من غير الصحيح محاولة تحديد قيمة جديدة من هذا النوع أو محاولة تبديل قيمة موجودة إلى هذا النوع. |

### أنظر أيضا

* class [SVGValueType](../svgvaluetype/)
* مساحة الاسم [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* المجسم [Aspose.HTML](../../)


