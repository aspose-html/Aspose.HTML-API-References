---
title: "فئة Color"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "الفئة com.aspose.html.drawing.Color. تسمح لك فئة Color بتحديد الألوان كقيم Red-Green-Blue RGB أو قيم Hue-Saturation-Luminosity HSL أو قيم Hue-Saturation-Value HSV أو قيم Hue-Whiteness-Blackness HWB أو قيم lightness-A-B LAB أو قيم Luminance-Chroma-Hue LCH أو قيم Cyan-Magenta-Yellow-Key CMYK أو قيم Natural colors NCOL أو باسم اللون. كما يتوفر قناة Alpha للإشارة إلى الشفافية."
type: docs

url: /ar/java/com.aspose.html.drawing/color/
---
## Color class

تسمح لك فئة Color بتحديد الألوان كقيم Red-Green-Blue (RGB)، Hue-Saturation-Luminosity (HSL)، Hue-Saturation-Value (HSV)، Hue-Whiteness-Blackness (HWB)، lightness-A-B (LAB)، Luminance-Chroma-Hue (LCH)، Cyan-Magenta-Yellow-Key (CMYK)، Natural colors (NCOL) أو باستخدام اسم اللون. كما يتوفر قناة Alpha للإشارة إلى الشفافية.

```java
public class Color
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Color](color/#constructor)() | يُنشئ مثيلاً جديداً من الفئة `Color`. بشكل افتراضي يكون اللون أسود. |
| [Color](color/#constructor_1)(byte, byte, byte) | يُنشئ مثيلاً جديداً من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-255. |
| [Color](color/#constructor_5)(float, float, float) | يُنشئ مثيلاً جديداً من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-1. |
| [Color](color/#constructor_3)(int, int, int) | يُنشئ مثيلاً جديداً من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | يُنشئ مثيلاً جديداً من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | يُنشئ مثيلاً جديداً من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | يُنشئ مثيلاً جديداً من الفئة `Color`. يجب أن تكون جميع مكونات اللون ضمن النطاق 0-255. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) يمثل المكوّن alpha للون. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) يمثل المكوّن الأزرق للون. |
| [getGreen](../../com.aspose.html.drawing/color/green/) يمثل المكوّن الأخضر للون. |
| [getRed](../../com.aspose.html.drawing/color/red/) يمثل المكوّن الأحمر للون |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | يعيد Color جديداً بالقيم المطلوبة للسيان، الماجنتا، الأصفر، المفتاح (الأسود). |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | يعيد Color جديداً بالقيم المطلوبة للسيان، الماجنتا، الأصفر، المفتاح (الأسود)، وalpha. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | يعيد Color جديداً بالقيمة المطلوبة للرمادي. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | يعيد Color جديداً بالقيم المطلوبة للدرجة، التشبع، التشبع. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | يعيد Color جديداً بالقيم المطلوبة للدرجة، التشبع، التشبع، وalpha. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | يعيد Color جديداً بالقيم المطلوبة للدرجة، التشبع، القيمة. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | يعيد Color جديداً بالقيم المطلوبة للدرجة، التشبع، القيمة، وalpha. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | يعيد Color جديداً بالقيم المطلوبة للدرجة، البياض، السواد. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | يعيد Color جديداً بالقيم المطلوبة للدرجة، البياض، السواد. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | يعيد Color جديداً بالقيمة المطلوبة لـ ARGB. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | يعيد Color جديداً بالقيم المطلوبة للسطوع، A، B. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | يعيد Color جديدًا مع قيم الإضاءة المطلوبة، A، B، وalpha. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | يعيد Color جديدًا مع قيم luminance، chroma، hue المطلوبة. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | يعيد Color جديدًا مع قيم luminance، chroma، hue، وalpha المطلوبة. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | يعيد Color جديدًا مع قيم lightness، A، B المطلوبة لنموذج OKLAB. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | يعيد Color جديدًا مع قيم lightness، A، B، وalpha المطلوبة لنموذج OKLAB. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | يعيد Color جديدًا مع قيم luminance، chroma، hue المطلوبة لنموذج OKLAB. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | يعيد Color جديدًا مع قيم luminance، chroma، hue، وalpha المطلوبة لنموذج OKLAB. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | يعيد Color جديدًا مع قيم ged، green، blue المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | يعيد Color جديدًا مع قيم ged، green، blue المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | يعيد Color جديدًا مع قيم ged، green، blue المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | يعيد Color جديدًا مع قيم ged، green، blue، alpha المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | يعيد Color جديدًا مع قيم ged، green، blue، alpha المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | يعيد Color جديدًا مع قيم ged، green، blue، alpha المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | يحلل String يحتوي على لون CSS ويعيد Color جديدًا. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | يعيد Color جديداً بالقيمة المطلوبة لـ ARGB. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | ينشئ نسخة من Color مع مجموع luminance وقيمة delta. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | يعيد مكونات اللون بالتنسيق الخاص بنموذج اللون المحدد. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | يحدد ما إذا كان `Color` المحدد يساوي هذه الحالة. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | يعيد لونًا جديدًا يقع على الجانب المقابل لعجلة الألوان من الأصل. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | يعيد رمز تجزئة. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | يعيد Hue للـ Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | يعيد luminosity للـ Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | يعيد saturation للـ Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | يقوم بترميز مكونات ARGB للـ Color إلى int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | يعيد اسم اللون إذا كان يطابق لونًا في قائمة ألوان CSS المسماة، أو String فارغ. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | يعيد لون Natural colors (NCol) المحدد باستخدام حرف اللون مع رقم لتحديد المسافة (نسبةً مئوية) من اللون. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | يعيد لون Hexadecimal محدد بـ: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | يعيد String يحتوي على لون RGBA المحدد بـ: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | يعيد لونًا سداسيًا عشريًا يُحدَّد بـ: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | يعيد سلسلة تحتوي على لون RGB المحدد بـ: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | يعيد سلسلة تتكون من قيم مكوّنات RGBA. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | يقوم بترميز مكوّنات اللون ARGB إلى عدد صحيح غير موقع. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | ينشئ نسخة من اللون مع مكوّن ألفا المحدد. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | ينشئ نسخة من اللون مع درجة اللون المحددة. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | ينشئ نسخة من اللون مع الإضاءة المحددة. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | ينشئ نسخة من اللون مع التشبع المحدد. |

### انظر أيضًا

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
