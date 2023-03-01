---
title: Class Color
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Drawing.Color فصل. تتيح لك فئة اللون تحديد الألوان مثل قيم الأحمرالأخضرالأزرق RGB  HueSaturationLuminosity HSL  HueSaturationValue HSV  HueWhiteenessBlackness HWB  القيم  قيم lightnessAB LAB  قيم LuminanceChromaHue LCH  قيم CyanMagentaYellowKey CMYK  قيم الألوان الطبيعية NCOL  أو باسم لون . تتوفر أيضًا قناة Alpha للإشارة إلى الشفافية.
type: docs
weight: 2640
url: /ar/net/aspose.html.drawing/color/
---
## Color class

تتيح لك فئة اللون تحديد الألوان مثل قيم الأحمر-الأخضر-الأزرق (RGB) ، Hue-Saturation-Luminosity (HSL) ، Hue-Saturation-Value (HSV) ، Hue-Whiteeness-Blackness (HWB ) القيم ، قيم lightness-AB (LAB) ، قيم Luminance-Chroma-Hue (LCH) ، قيم Cyan-Magenta-Yellow-Key (CMYK) ، قيم الألوان الطبيعية (NCOL) ، أو باسم لون . تتوفر أيضًا قناة Alpha للإشارة إلى الشفافية.

```csharp
public class Color
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Color](color/#constructor)() | يقوم بتهيئة مثيل جديد لملف`Color` class. اللون الافتراضي هو الأسود. |
| [Color](color/#constructor_1)(byte, byte, byte) | يقوم بتهيئة مثيل جديد لملف`Color`class. يجب أن تكون كافة مكونات الألوان في النطاق 0-255. |
| [Color](color/#constructor_5)(float, float, float) | يقوم بتهيئة مثيل جديد لملف`Color` class. يجب أن تكون جميع مكونات الألوان في النطاق 0-1. |
| [Color](color/#constructor_3)(int, int, int) | يقوم بتهيئة مثيل جديد لملف`Color`class. يجب أن تكون كافة مكونات الألوان في النطاق 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | يقوم بتهيئة مثيل جديد لملف`Color`class. يجب أن تكون كافة مكونات الألوان في النطاق 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | يقوم بتهيئة مثيل جديد لملف`Color` class. يجب أن تكون جميع مكونات الألوان في النطاق 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | يقوم بتهيئة مثيل جديد لملف`Color`class. يجب أن تكون كافة مكونات الألوان في النطاق 0-255. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | يمثل مكون ألفا للون. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | يمثل المكون الأزرق للون. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | يمثل المكون الأخضر للون. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | يمثل المكون الأحمر للون |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | إرجاع لون جديد بقيم السماوي والأرجواني والأصفر والمفتاح (الأسود) المطلوبة. |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | إرجاع لون جديد بقيم ألفا سماوي وأرجواني وأصفر ومفتاح (أسود) وقيم ألفا. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | إرجاع لون جديد بقيمة الرمادية المطلوبة. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | إرجاع لون جديد بقيم الصبغة والتشبع والتشبع المطلوبة. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | إرجاع لون جديد مع تدرج اللون المطلوب ، والتشبع ، والتشبع ، وقيم ألفا. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | إرجاع لون جديد بالتدرج المطلوب ، والتشبع ، والقيمة. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | إرجاع لون جديد بالتدرج المطلوب ، والتشبع ، والقيمة ، و alpha. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | إرجاع لون جديد بقيم درجة اللون ، البياض ، السواد المطلوبة. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | إرجاع لون جديد بقيم درجة اللون ، البياض ، السواد المطلوبة. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | إرجاع لون جديد بقيمة ARGB المطلوبة. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | إرجاع لون جديد بقيم الإضاءة A و B المطلوبة. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | إرجاع لون جديد بقيم ألفا ، A ، B ، الخفة المطلوبة. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | إرجاع لون جديد بقيم النصوع والصفاء ودرجة اللون المطلوبة. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | إرجاع لون جديد مع قيم النصوع والصفاء وتدرج اللون وقيم ألفا المطلوبة. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | إرجاع لون جديد بقيم الإضاءة A و B المطلوبة لنموذج OKLAB. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | إرجاع لون جديد بقيم ألفا ، A ، B ، الخفة المطلوبة لنموذج OKLAB. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | إرجاع لون جديد مع قيم النصوع والصفاء ودرجة اللون المطلوبة لنموذج OKLAB. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | إرجاع لون جديد مع قيم النصوع والصفاء وتدرج اللون وقيم ألفا المطلوبة لنموذج OKLAB. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | إرجاع لون جديد بقيم ged والأخضر والأزرق المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | إرجاع لون جديد بقيم ged والأخضر والأزرق المطلوبة. يجب أن تكون كافة مكونات اللون في النطاق 0-1 . |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | إرجاع لون جديد بقيم ged والأخضر والأزرق المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | إرجاع لون جديد بقيم ألفا ، الأخضر ، الأزرق ، ged المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | إرجاع لون جديد بقيم ألفا ، الأخضر ، الأزرق ، ged المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-1 . |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | إرجاع لون جديد بقيم ألفا ، الأخضر ، الأزرق ، ged المطلوبة. يجب أن تكون جميع مكونات اللون في النطاق 0-255. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | يوزع سلسلة تحتوي على لون CSS وتُرجع لونًا جديدًا. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | إرجاع لون جديد بقيمة ARGB المطلوبة. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | لإنشاء نسخة من اللون مع مجموع لمعانها وقيمة دلتا. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | إرجاع مكونات اللون بتنسيق نموذج اللون المحدد. |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | تحديد ما إذا كان الملف المحدد`Color` يساوي هذا المثال. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | إرجاع لون جديد موجود على الجانب الآخر من عجلة الألوان من الأصل. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | إرجاع رمز تجزئة . |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | إرجاع تدرج اللون. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | إرجاع لمعان اللون. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | إرجاع تشبع اللون. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | لتشفير مكونات Color ARGB في int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | إرجاع اسم اللون إذا كان يطابق لونًا في قائمة ألوان CSS المسماة ، أو سلسلة فارغة. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | إرجاع اللون المحدد للألوان الطبيعية (NCol) باستخدام حرف ملون مع رقم لتحديد المسافة (بالنسبة المئوية) من اللون. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | إرجاع تحديد لون سداسي عشري بـ: # RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | إرجاع سلسلة تحتوي على لون RGBA المحدد بواسطة: rgba (R ، G ، B ، A) . |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | إرجاع لون سداسي عشري محدد بـ: # RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | إرجاع سلسلة تحتوي على لون RGB المحدد بواسطة: rgb (R ، G ، B) . |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | إرجاع سلسلة تتكون من قيم مكون RGBA. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | ترميز مكونات Color ARGB إلى عدد صحيح غير موقعة. |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | إنشاء نسخة من اللون بمكون ألفا محدد. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | لإنشاء نسخة من اللون مع تدرج اللون المحدد. |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | إنشاء نسخة من اللون بالسطوع المحدد. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | إنشاء نسخة من اللون بالتشبع المحدد. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Drawing](../../aspose.html.drawing/)
* المجسم [Aspose.HTML](../../)


