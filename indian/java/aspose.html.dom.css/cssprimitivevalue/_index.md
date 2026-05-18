---
title: "CSSPrimitiveValue क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.CSSPrimitiveValue क्लास। CSSPrimitiveValue इंटरफ़ेस CSSValue इंटरफ़ेस से व्युत्पन्न है और CSS प्रॉपर्टी के वर्तमान गणना किए गए मान का प्रतिनिधित्व करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue इंटरफ़ेस CSSValue इंटरफ़ेस से व्युत्पन्न है और CSS प्रॉपर्टी के वर्तमान गणना किए गए मान का प्रतिनिधित्व करता है।

ध्यान दें: यह इंटरफ़ेस टाइप्ड CSS ऑब्जेक्ट मॉडल बनाने के प्रयास का हिस्सा था। इस प्रयास को छोड़ दिया गया है, और अधिकांश ब्राउज़र इसे लागू नहीं करते हैं।

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## गुण

| नाम | विवरण |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) इंटरफ़ेस की cssText प्रॉपर्टी वर्तमान गणना किए गए CSS प्रॉपर्टी मान को दर्शाती है। |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) मान के प्रकार को परिभाषित करने वाला कोड। |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) ऊपर निर्दिष्ट स्थिरांक द्वारा परिभाषित मान का प्रकार। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है या नहीं। |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | यह मेथड काउंटर मान प्राप्त करने के लिए उपयोग किया जाता है। यदि यह CSS मान काउंटर मान नहीं रखता है, तो एक DOMException उत्पन्न किया जाता है। संबंधित स्टाइल प्रॉपर्टी में संशोधन काउंटर इंटरफ़ेस का उपयोग करके किया जा सकता है। |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | यह विधि निर्दिष्ट इकाई में एक फ्लोट मान प्राप्त करने के लिए उपयोग की जाती है। यदि इस CSS मान में फ्लोट मान नहीं है या इसे निर्दिष्ट इकाई में परिवर्तित नहीं किया जा सकता, तो एक DOMException उठाया जाता है। |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | इस उदाहरण के लिए हैश कोड लौटाता है। |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | यह विधि निर्दिष्ट इकाई में एक इंट मान प्राप्त करने के लिए उपयोग की जाती है। यदि इस CSS मान में इंट मान नहीं है या इसे निर्दिष्ट इकाई में परिवर्तित नहीं किया जा सकता, तो एक DOMException उठाया जाता है। |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट टाइप प्राप्त करने के लिए उपयोग किया जाता है। |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | यह विधि Rect मान प्राप्त करने के लिए उपयोग की जाती है। यदि इस CSS मान में Rect मान नहीं है, तो एक DOMException उठाया जाता है। संबंधित शैली गुण में संशोधन Rect इंटरफ़ेस का उपयोग करके किया जा सकता है। |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | यह विधि RGB रंग प्राप्त करने के लिए उपयोग की जाती है। यदि इस CSS मान में RGB रंग मान नहीं है, तो एक DOMException उठाया जाता है। संबंधित शैली गुण में संशोधन RGBColor इंटरफ़ेस का उपयोग करके किया जा सकता है। |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | यह विधि String मान प्राप्त करने के लिए उपयोग की जाती है। यदि CSS मान में String मान नहीं है, तो एक DOMException उठाया जाता है। |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | निर्दिष्ट इकाई के साथ फ्लोट मान सेट करने की एक विधि। यदि इस मान से जुड़ी संपत्ति निर्दिष्ट इकाई या फ्लोट मान को स्वीकार नहीं कर सकती, तो मान अपरिवर्तित रहेगा और एक DOMException उठाया जाएगा। |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | निर्दिष्ट इकाई के साथ इंट मान सेट करने की एक विधि। यदि इस मान से जुड़ी संपत्ति निर्दिष्ट इकाई या इंट मान को स्वीकार नहीं कर सकती, तो मान अपरिवर्तित रहेगा और एक DOMException उठाया जाएगा। |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | निर्दिष्ट इकाई के साथ String मान सेट करने की एक विधि। यदि इस मान से जुड़ी संपत्ति निर्दिष्ट इकाई या String मान को स्वीकार नहीं कर सकती, तो मान अपरिवर्तित रहेगा और एक DOMException उठाया जाएगा। |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | यह मान एक एट्रिब्यूट फ़ंक्शन है। यह मान getStringValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | यह मान एक लंबाई (ch) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | यह मान एक लंबाई (cm) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | यह मान एक काउंटर या काउंटरस फ़ंक्शन है। यह मान GetCounterValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | यह मान एक कोण (deg) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | यह मान एक अज्ञात आयाम वाला संख्या है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | यह मान सेंटीमीटर प्रति डॉट (dpcm) है। |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | यह मान इंच प्रति डॉट (dpi) है। |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | यह मान ‘px’ इकाई प्रति डॉट (dppx) है। |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | यह मान एक लंबाई (ems) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | यह मान एक लंबाई (exs) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | यह मान एक कोण (grad) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | यह मान एक आवृत्ति (Hz) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | यह मान एक पहचानकर्ता है। यह मान getStringValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | यह मान एक लंबाई (in) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | यह मान एक आवृत्ति (kHz) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | यह मान एक लंबाई (mm) है। यह मान getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | मान एक समय (ms) है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | मान एक साधारण संख्या है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | मान एक लंबाई (pc) है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | मान एक प्रतिशत है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | मान एक लंबाई (pt) है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | मान एक लंबाई (px) है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | मान एक कोण (rad) है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | मान एक rect फ़ंक्शन है। मान को GetRectValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | मान एक लंबाई (rem) है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | मान एक RGB रंग है। मान को GetRGBColorValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | मान एक समय (s) है। मान को getFloatValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | मान एक STRING है। मान को getStringValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | मान एक मान्यता प्राप्त CSS2 मान नहीं है। मान को केवल cssText एट्रिब्यूट का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | मान एक URI है। मान को getStringValue मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | मान पूर्ण व्यूपोर्ट ऊँचाई का प्रतिशत है। |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | मान व्यूपोर्ट की चौड़ाई या ऊँचाई का प्रतिशत है, जो भी बड़ा हो। |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | मान व्यूपोर्ट की चौड़ाई या ऊँचाई का प्रतिशत है, जो भी छोटा हो। |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | मान पूर्ण व्यूपोर्ट चौड़ाई का प्रतिशत है। |

### संबंधित देखें

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
