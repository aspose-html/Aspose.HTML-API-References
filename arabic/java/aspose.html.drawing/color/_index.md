---
title: "فئة Color"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.drawing.Color. تتيح لك فئة Color تحديد الألوان كقيم Red-Green-Blue RGB أو قيم Hue-Saturation-Luminosity HSL أو قيم Hue-Saturation-Value HSV أو قيم Hue-Whiteness-Blackness HWB أو قيم lightness-A-B LAB أو قيم Luminance-Chroma-Hue LCH أو قيم Cyan-Magenta-Yellow-Key CMYK أو قيم Natural colors NCOL أو باستخدام اسم اللون. كما يتوفر قناة Alpha للإشارة إلى الشفافية."
type: docs

url: /ar/java/com.aspose.html.drawing/color/
---
## Color class

تتيح لك فئة Color تحديد الألوان كقيم Red-Green-Blue (RGB)، وقيم Hue-Saturation-Luminosity (HSL)، وقيم Hue-Saturation-Value (HSV)، وقيم Hue-Whiteness-Blackness (HWB)، وقيم lightness-A-B (LAB)، وقيم Luminance-Chroma-Hue (LCH)، وقيم Cyan-Magenta-Yellow-Key (CMYK)، وقيم Natural colors (NCOL)، أو باسم اللون. كما يتوفر قناة Alpha للإشارة إلى الشفافية.

```java
public class Color
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Color](color/#constructor)() | ينشئ مثيلًا جديدًا من الفئة `Color`. اللون الافتراضي هو الأسود. |
| [Color](color/#constructor_1)(byte, byte, byte) | ينشئ مثيلًا جديدًا من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-255. |
| [Color](color/#constructor_5)(float, float, float) | ينشئ مثيلًا جديدًا من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-1. |
| [Color](color/#constructor_3)(int, int, int) | ينشئ مثيلًا جديدًا من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | ينشئ مثيلًا جديدًا من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | ينشئ مثيلًا جديدًا من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | ينشئ مثيلًا جديدًا من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-255. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) يمثل مكون alpha للون. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) يمثل مكون الأزرق للون. |
| [getGreen](../../com.aspose.html.drawing/color/green/) يمثل مكون الأخضر للون. |
| [getRed](../../com.aspose.html.drawing/color/red/) يمثل مكون الأحمر للون |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للسيان، الماجنتا، الأصفر، المفتاح (الأسود). |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للسيان، الماجنتا، الأصفر، المفتاح (الأسود)، وalpha. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | يعيد Color جديدًا بقيمة الرمادي المطلوبة. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للدرجة (hue)، التشبع، التشبع. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للدرجة (hue)، التشبع، التشبع، وalpha. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للدرجة (hue)، التشبع، القيمة. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للدرجة (hue)، التشبع، القيمة، وalpha. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للدرجة (hue)، البياض، السواد. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للدرجة (hue)، البياض، السواد. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | يعيد Color جديدًا بقيمة ARGB المطلوبة. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | يعيد Color جديدًا بالقيم المطلوبة للسطوع، A، B. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | يرجع Color جديدًا مع قيم lightness، A، B، alpha المطلوبة. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | يرجع Color جديدًا مع قيم luminance، chroma، hue المطلوبة. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | يرجع Color جديدًا مع قيم luminance، chroma، hue، alpha المطلوبة. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | يرجع Color جديدًا مع قيم lightness، A، B المطلوبة لنموذج OKLAB. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | يرجع Color جديدًا مع قيم lightness، A، B، alpha المطلوبة لنموذج OKLAB. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | يرجع Color جديدًا مع قيم luminance، chroma، hue المطلوبة لنموذج OKLAB. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | يرجع Color جديدًا مع قيم luminance، chroma، hue، alpha المطلوبة لنموذج OKLAB. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | يرجع Color جديدًا مع قيم ged، green، blue المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | يرجع Color جديدًا مع قيم ged، green، blue المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | يرجع Color جديدًا مع قيم ged، green، blue المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | يرجع Color جديدًا مع قيم ged، green، blue، alpha المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | يرجع Color جديدًا مع قيم ged، green، blue، alpha المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | يرجع Color جديدًا مع قيم ged، green، blue، alpha المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | يقوم بتحليل String التي تحتوي على لون CSS ويعيد Color جديد. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | يعيد Color جديدًا بقيمة ARGB المطلوبة. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | ينشئ نسخة من Color مع مجموع luminosity وقيمة الدلتا. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | يرجع مكونات اللون بالتنسيق الخاص بنموذج اللون المحدد. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | يحدد ما إذا كان `Color` المحدد يساوي هذه الحالة. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | يرجع لونًا جديدًا يقع على الجانب المقابل لعجلة الألوان من الأصل. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | يرجع رمز تجزئة. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | يرجع Hue للـ Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | يرجع luminosity للـ Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | يرجع saturation للـ Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | يقوم بترميز مكونات ARGB للـ Color إلى int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | يرجع اسم اللون إذا كان يطابق لونًا في قائمة ألوان CSS المسماة، أو String فارغ. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | يرجع لونًا Natural colors (NCol) المحدد باستخدام حرف اللون مع رقم لتحديد المسافة (بالنسبة المئوية) من اللون. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | يرجع لونًا سداسيًا عشريًا يُحدد بـ: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | يرجع String يحتوي على لون RGBA المحدد بـ: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | إرجاع لون سداسي عشري يُحدد بـ: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | إرجاع سلسلة تحتوي على لون RGB المحدد بـ: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | إرجاع سلسلة تتكون من قيم مكونات RGBA. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | يشفّر مكونات اللون ARGB إلى عدد صحيح غير موقع. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | إنشاء نسخة من اللون مع مكون ألفا المحدد. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | إنشاء نسخة من اللون مع درجة اللون المحددة. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | إنشاء نسخة من اللون مع السطوع المحدد. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | إنشاء نسخة من اللون مع التشبع المحدد. |

### انظر أيضًا

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
