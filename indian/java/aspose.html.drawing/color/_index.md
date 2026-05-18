---
title: "Color क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.drawing.Color क्लास। Color क्लास आपको रंगों को Red-Green-Blue RGB मान, Hue-Saturation-Luminosity HSL मान, Hue-Saturation-Value HSV मान, Hue-Whiteness-Blackness HWB मान, lightness-A-B LAB मान, Luminance-Chroma-Hue LCH मान, Cyan-Magenta-Yellow-Key CMYK मान, Natural colors NCOL मान या रंग नाम से निर्दिष्ट करने देता है। पारदर्शिता दर्शाने के लिए एक Alpha चैनल भी उपलब्ध है।"
type: docs

url: /hi/java/com.aspose.html.drawing/color/
---
## Color class

Color क्लास आपको रंगों को Red-Green-Blue (RGB) मान, Hue-Saturation-Luminosity (HSL) मान, Hue-Saturation-Value (HSV) मान, Hue-Whiteness-Blackness (HWB) मान, lightness-A-B (LAB) मान, Luminance-Chroma-Hue (LCH) मान, Cyan-Magenta-Yellow-Key (CMYK) मान, Natural colors (NCOL) मान, या रंग नाम से निर्दिष्ट करने देता है। एक Alpha चैनल भी उपलब्ध है जो पारदर्शिता दर्शाता है।

```java
public class Color
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Color](color/#constructor)() | `Color` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। डिफ़ॉल्ट रूप से रंग काला है। |
| [Color](color/#constructor_1)(byte, byte, byte) | `Color` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। सभी रंग घटकों का मान 0-255 की सीमा में होना चाहिए। |
| [Color](color/#constructor_5)(float, float, float) | `Color` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। सभी रंग घटकों का मान 0-1 की सीमा में होना चाहिए। |
| [Color](color/#constructor_3)(int, int, int) | `Color` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। सभी रंग घटकों का मान 0-255 की सीमा में होना चाहिए। |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | `Color` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। सभी रंग घटकों का मान 0-255 की सीमा में होना चाहिए। |
| [Color](color/#constructor_6)(float, float, float, float) | `Color` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। सभी रंग घटकों का मान 0-1 की सीमा में होना चाहिए। |
| [Color](color/#constructor_4)(int, int, int, int) | `Color` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। सभी रंग घटकों का मान 0-255 की सीमा में होना चाहिए। |

## गुण

| नाम | विवरण |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) रंग के अल्फा घटक का प्रतिनिधित्व करता है। |
| [getBlue](../../com.aspose.html.drawing/color/blue/) रंग के नीले घटक का प्रतिनिधित्व करता है। |
| [getGreen](../../com.aspose.html.drawing/color/green/) रंग के हरे घटक का प्रतिनिधित्व करता है। |
| [getRed](../../com.aspose.html.drawing/color/red/) रंग के लाल घटक का प्रतिनिधित्व करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | अनुरोधित cyan, magenta, yellow, key (black) मानों के साथ एक नया Color लौटाता है। |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | अनुरोधित cyan, magenta, yellow, key (black), alpha मानों के साथ एक नया Color लौटाता है। |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | अनुरोधित ग्रे मान के साथ एक नया Color लौटाता है। |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | अनुरोधित hue, saturation, saturation मानों के साथ एक नया Color लौटाता है। |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | अनुरोधित hue, saturation, saturation, alpha मानों के साथ एक नया Color लौटाता है। |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | अनुरोधित hue, saturation, value के साथ एक नया Color लौटाता है। |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | अनुरोधित hue, saturation, value, alpha के साथ एक नया Color लौटाता है। |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | अनुरोधित hue, whiteness, blackness मानों के साथ एक नया Color लौटाता है। |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | अनुरोधित hue, whiteness, blackness मानों के साथ एक नया Color लौटाता है। |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | अनुरोधित ARGB मान के साथ एक नया Color लौटाता है। |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | अनुरोधित lightness, A, B मानों के साथ एक नया Color लौटाता है। |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | अनुरोधित लाइटनेस, A, B, अल्फा मानों के साथ एक नया Color लौटाता है। |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | अनुरोधित ल्यूमिनेंस, क्रोमा, ह्यू मानों के साथ एक नया Color लौटाता है। |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | अनुरोधित ल्यूमिनेंस, क्रोमा, ह्यू, अल्फा मानों के साथ एक नया Color लौटाता है। |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | OKLAB मॉडल के लिए अनुरोधित लाइटनेस, A, B मानों के साथ एक नया Color लौटाता है। |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | OKLAB मॉडल के लिए अनुरोधित लाइटनेस, A, B, अल्फा मानों के साथ एक नया Color लौटाता है। |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | OKLAB मॉडल के लिए अनुरोधित ल्यूमिनेंस, क्रोमा, ह्यू मानों के साथ एक नया Color लौटाता है। |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | OKLAB मॉडल के लिए अनुरोधित ल्यूमिनेंस, क्रोमा, ह्यू, अल्फा मानों के साथ एक नया Color लौटाता है। |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | अनुरोधित GED, ग्रीन, ब्लू मानों के साथ एक नया Color लौटाता है। सभी रंग घटकों का मान 0-255 की सीमा में होना चाहिए। |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | अनुरोधित GED, ग्रीन, ब्लू मानों के साथ एक नया Color लौटाता है। सभी रंग घटकों का मान 0-1 की सीमा में होना चाहिए। |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | अनुरोधित GED, ग्रीन, ब्लू मानों के साथ एक नया Color लौटाता है। सभी रंग घटकों का मान 0-255 की सीमा में होना चाहिए। |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | अनुरोधित GED, ग्रीन, ब्लू, अल्फा मानों के साथ एक नया Color लौटाता है। सभी रंग घटकों का मान 0-255 की सीमा में होना चाहिए। |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | अनुरोधित GED, ग्रीन, ब्लू, अल्फा मानों के साथ एक नया Color लौटाता है। सभी रंग घटकों का मान 0-1 की सीमा में होना चाहिए। |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | अनुरोधित GED, ग्रीन, ब्लू, अल्फा मानों के साथ एक नया Color लौटाता है। सभी रंग घटकों का मान 0-255 की सीमा में होना चाहिए। |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | CSS रंग को समाहित करने वाली स्ट्रिंग को पार्स करता है और एक नया Color लौटाता है। |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | अनुरोधित ARGB मान के साथ एक नया Color लौटाता है। |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Color की ल्यूमिनेंस और डेल्टा मान के योग के साथ उसकी एक प्रति बनाता है। |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | निर्दिष्ट रंग मॉडल के फ़ॉर्मेट में रंग घटकों को लौटाता है। |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | निर्धारित करता है कि निर्दिष्ट `Color` इस इंस्टेंस के बराबर है या नहीं। |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | मूल Color के विपरीत दिशा में रंग पहिया पर स्थित एक नया रंग लौटाता है। |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | एक हैश कोड लौटाता है। |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Color का ह्यू लौटाता है। |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Color की ल्यूमिनेंस लौटाता है। |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Color की सैचुरेशन लौटाता है। |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Color के ARGB घटकों को int में एन्कोड करता है। |
| [toName](../../com.aspose.html.drawing/color/toname/)() | यदि रंग CSS नामित रंगों की सूची में मौजूद है तो उसका नाम लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | एक Natural colors (NCol) निर्दिष्ट रंग को एक रंग अक्षर के साथ संख्या का उपयोग करके रंग से दूरी (प्रतिशत में) निर्दिष्ट करके लौटाता है। |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Hexadecimal रंग इस प्रकार निर्दिष्ट किया जाता है: #RRGGBBAA। |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | rgba(R, G, B, A) द्वारा निर्दिष्ट RGBA रंग को समाहित करने वाली स्ट्रिंग लौटाता है। |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | एक हेक्साडेसिमल रंग लौटाता है जिसे इस प्रकार निर्दिष्ट किया जाता है: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | एक स्ट्रिंग लौटाता है जिसमें RGB रंग शामिल है जिसे इस प्रकार निर्दिष्ट किया गया है: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | एक स्ट्रिंग लौटाता है जिसमें RGBA घटक मान शामिल हैं। |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | रंग के ARGB घटकों को अनसाइन्ड इंट में एन्कोड करता है। |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | निर्दिष्ट अल्फा घटक के साथ रंग की एक कॉपी बनाता है। |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | निर्दिष्ट ह्यू के साथ रंग की एक कॉपी बनाता है। |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | निर्दिष्ट चमक के साथ रंग की एक कॉपी बनाता है। |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | निर्दिष्ट संतृप्ति के साथ रंग की एक कॉपी बनाता है। |

### संबंधित देखें

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
