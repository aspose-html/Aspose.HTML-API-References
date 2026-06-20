---
title: "الفئة SVGAngle"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.dom.svg.datatypes.SVGAngle. واجهة SVGAngle تتطابق مع نوع البيانات الأساسي angle."
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
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | احتفظ بنفس القيمة المخزنة الأساسية، ولكن أعد تعيين معرف الوحدة المخزنة إلى unitType المعطى. قد يتم تعديل سمات الكائن unitType و valueInSpecifiedUnits و valueAsString نتيجةً لهذه الطريقة. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة - واختياريًا - المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | أعد تعيين القيمة كعدد مع unitType مرتبط، وبالتالي استبدال القيم لجميع السمات على الكائن. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | يعيد سلسلة تمثل هذا الكائن. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | تم تعيين نوع الوحدة صراحةً إلى درجات. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | نوع الوحدة هو راديان. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | نوع الوحدة هو راديان. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | نوع الوحدة ليس أحد أنواع الوحدات المعرفة مسبقًا. من غير الصالح محاولة تعريف قيمة جديدة من هذا النوع أو محاولة تحويل قيمة موجودة إلى هذا النوع. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | لم يتم توفير نوع وحدة (أي تم تحديد قيمة بدون وحدة). بالنسبة للزوايا، تُعامل القيمة بدون وحدة كما لو تم تحديد درجات. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
