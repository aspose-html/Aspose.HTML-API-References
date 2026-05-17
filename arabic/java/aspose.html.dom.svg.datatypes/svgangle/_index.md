---
title: "فئة SVGAngle"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "الفئة com.aspose.html.dom.svg.datatypes.SVGAngle. الواجهة SVGAngle تتطابق مع نوع البيانات الأساسي angle."
type: docs

url: /ar/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

واجهة SVGAngle تتطابق مع نوع البيانات الأساسي angle.

```java
public class SVGAngle : SVGValueType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) نوع القيمة كما هو محدد بأحد الثوابت SVG_ANGLETYPE_* المعرفة في هذه الواجهة. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | احتفظ بنفس القيمة المخزنة الأساسية، ولكن أعد ضبط معرف الوحدة المخزنة إلى unitType المحدد. قد يتم تعديل خصائص الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجةً لهذا الأسلوب. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و - اختياريًا - الموارد المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | أعد ضبط القيمة كعدد مرتبط بـ unitType، وبالتالي استبدال القيم لجميع الخصائص على الكائن. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | يرجع سلسلة تمثل هذا الكائن. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | تم تعيين نوع الوحدة صراحةً إلى درجات. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | نوع الوحدة هو راديان. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | نوع الوحدة هو راديان. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | نوع الوحدة ليس أحد الأنواع المعرفة مسبقًا. من غير الصالح محاولة تعريف قيمة جديدة من هذا النوع أو محاولة تحويل قيمة موجودة إلى هذا النوع. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | لم يتم توفير نوع وحدة (أي تم تحديد قيمة بلا وحدة). بالنسبة للزوايا، تُعامل القيمة بلا وحدة كما لو تم تحديدها بالدرجات. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
