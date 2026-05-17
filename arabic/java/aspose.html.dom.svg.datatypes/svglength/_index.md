---
title: "فئة SVGLength"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.svg.datatypes.SVGLength. واجهة SVGLength تتطابق مع نوع البيانات الأساسي للطول. يمكن تعيين كائن SVGLength على أنه للقراءة فقط مما يعني أن محاولات تعديل الكائن ستؤدي إلى استثناء يُرمى كما هو موضح أدناه."
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

واجهة SVGLength تتطابق مع نوع البيانات الأساسي للطول. يمكن تعيين كائن SVGLength على أنه للقراءة فقط، مما يعني أن محاولات تعديل الكائن ستؤدي إلى رمي استثناء، كما هو موضح أدناه.

```java
public class SVGLength : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) نوع القيمة كما هو محدد بأحد الثوابت SVG_LENGTHTYPE_* المعرفة على هذه الواجهة. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | حافظ على نفس القيمة المخزنة الأساسية، ولكن أعد ضبط معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجة لهذه الطريقة. على سبيل المثال، إذا كانت القيمة الأصلية "0.5cm" وتم استدعاء الطريقة لتحويلها إلى مليمترات، فسيتم تغيير unitType إلى SVG_LENGTHTYPE_MM، وستتغير valueInSpecifiedUnits إلى القيمة الرقمية 5، وستتغير valueAsString إلى "5mm". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و - اختياريًا - الموارد المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | أعد ضبط القيمة كعدد مرتبط بـ unitType، وبالتالي استبدال القيم لجميع الخصائص على الكائن. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | يرجع سلسلة تمثل هذا الكائن. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | تم تحديد قيمة باستخدام وحدات cm المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | تم تحديد قيمة باستخدام وحدات em المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | تم تحديد قيمة باستخدام وحدات ex المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | تم تحديد قيمة باستخدام وحدات in المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | تم تحديد قيمة باستخدام وحدات mm المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | لم يتم توفير نوع وحدة (أي تم تحديد قيمة بدون وحدة)، مما يشير إلى قيمة بوحدات المستخدم. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | تم تحديد قيمة باستخدام وحدات pc المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | تم تحديد قيمة نسبة مئوية. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | تم تحديد قيمة باستخدام وحدات pt المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | تم تحديد قيمة باستخدام وحدات px المعرفة في CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | نوع الوحدة ليس أحد الأنواع المعرفة مسبقًا. من غير الصالح محاولة تعريف قيمة جديدة من هذا النوع أو محاولة تحويل قيمة موجودة إلى هذا النوع. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
