---
title: Class CSSPrimitiveValue
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Css.CSSPrimitiveValue कक्ष. CSSPrimitiveValue इंटरफ़ेस एक एकल CSS मन क प्रतनधत्व करत है इस इंटरफ़ेस क उपयग कस ब्लक में वर्तमन में सेट क गई वशष्ट शैल क संपत्त के मूल्य क नर्धरत करने के लए य स्पष्ट रूप से ब्लक के भतर एक वशष्ट शैल क संपत्त क सेट करने के लए कय ज सकत है इस इंटरफ़ेस क एक उदहरण CSSStyleDeclaration इंटरफ़ेस क getPropertyCSSValue वध से प्रप्त कय ज सकत है CSSPrimitiveValue ऑब्जेक्ट केवल CSS गुण के संदर्भ में हत है.
type: docs
weight: 330
url: /hi/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue इंटरफ़ेस एक एकल CSS मान का प्रतिनिधित्व करता है। इस इंटरफ़ेस का उपयोग किसी ब्लॉक में वर्तमान में सेट की गई विशिष्ट शैली की संपत्ति के मूल्य को निर्धारित करने के लिए या स्पष्ट रूप से ब्लॉक के भीतर एक विशिष्ट शैली की संपत्ति को सेट करने के लिए किया जा सकता है। इस इंटरफ़ेस का एक उदाहरण CSSStyleDeclaration इंटरफ़ेस की getPropertyCSSValue विधि से प्राप्त किया जा सकता है। CSSPrimitiveValue ऑब्जेक्ट केवल CSS गुण के संदर्भ में होता है.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## गुण

| नाम | विवरण |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | वर्तमान मान का एक स्ट्रिंग प्रतिनिधित्व। |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | मान के प्रकार को परिभाषित करने वाला एक कोड। |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype/) { get; } | ऊपर निर्दिष्ट स्थिरांक द्वारा परिभाषित मान का प्रकार। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | निर्धारित करता है कि निर्दिष्ट किया गया है या नहींObject इस उदाहरण के बराबर है. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | इस विधि का उपयोग काउंटर वैल्यू प्राप्त करने के लिए किया जाता है। यदि इस CSS मान में काउंटर मान नहीं है, तो एक DOMException उठाया जाता है। काउंटर इंटरफ़ेस का उपयोग करके संबंधित शैली की संपत्ति में संशोधन प्राप्त किया जा सकता है। |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | इस विधि का उपयोग निर्दिष्ट इकाई में फ्लोट मान प्राप्त करने के लिए किया जाता है। यदि इस CSS मान में फ़्लोट मान नहीं है या उसे निर्दिष्ट इकाई में परिवर्तित नहीं किया जा सकता है, तो एक DOMException उठाया जाता है. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | इस उदाहरण के लिए एक हैश कोड लौटाता है। |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | इस विधि का उपयोग निर्दिष्ट इकाई में अंतर मान प्राप्त करने के लिए किया जाता है। यदि इस CSS मान में कोई अंतर मान नहीं है या इसे निर्दिष्ट इकाई में परिवर्तित नहीं किया जा सकता है, तो एक DOMException उठाया जाता है. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | इस विधि का उपयोग रेक्ट मान प्राप्त करने के लिए किया जाता है। यदि इस CSS मान में कोई आयत मान नहीं है, तो एक DOMException उठाया जाता है। रेक्ट इंटरफ़ेस का उपयोग करके संबंधित शैली की संपत्ति में संशोधन प्राप्त किया जा सकता है। |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | आरजीबी रंग प्राप्त करने के लिए इस विधि का उपयोग किया जाता है। यदि इस CSS मान में RGB रंग मान नहीं है, तो एक DOMException उठाया जाता है। संबंधित शैली गुण में संशोधन RGBColor इंटरफ़ेस का उपयोग करके प्राप्त किया जा सकता है. |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue/)() | इस विधि का उपयोग स्ट्रिंग मान प्राप्त करने के लिए किया जाता है। यदि CSS मान में कोई स्ट्रिंग मान नहीं है, तो एक DOMException उठाया जाता है. |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | निर्दिष्ट इकाई के साथ फ्लोट मान सेट करने की विधि। यदि इस मान से जुड़ी संपत्ति निर्दिष्ट इकाई या फ्लोट मान को स्वीकार नहीं कर सकती है, तो मान अपरिवर्तित रहेगा और एक DOMException उठाया जाएगा। |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | निर्दिष्ट इकाई के साथ अंतर मान सेट करने की विधि। यदि इस मान से जुड़ी संपत्ति निर्दिष्ट इकाई या int मान को स्वीकार नहीं कर सकती है, तो मान अपरिवर्तित रहेगा और एक DOMException उठाया जाएगा। |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | निर्दिष्ट इकाई के साथ स्ट्रिंग मान सेट करने की विधि। यदि इस मान से जुड़ी संपत्ति निर्दिष्ट इकाई या स्ट्रिंग मान को स्वीकार नहीं कर सकती है, तो मान अपरिवर्तित रहेगा और एक DOMException उठाया जाएगा। |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr/) | मान एक विशेषता फ़ंक्शन है। मान getStringValue विधि का उपयोग करके प्राप्त किया जा सकता है. |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch/) | मान लंबाई (ch) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm/) | मान लंबाई (सेमी) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter/) | मान एक काउंटर या काउंटर फ़ंक्शन है। GetCounterValue पद्धति का उपयोग करके मान प्राप्त किया जा सकता है. |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg/) | मान एक कोण (डिग्री) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension/) | मान एक अज्ञात आयाम वाली संख्या है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | मान डॉट्स प्रति सेंटीमीटर (डीपीसीएम) है। |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi/) | मान डॉट्स प्रति इंच (डीपीआई) है। |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx/) | मान डॉट्स प्रति 'पीएक्स' इकाई (डीपीपीएक्स) है। |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems/) | मान लंबाई (ईएमएस) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs/) | मान लंबाई (पूर्व) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad/) | मान एक कोण (ग्रेड) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz/) | मान एक आवृत्ति (Hz) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident/) | मान एक पहचानकर्ता है। मान getStringValue विधि का उपयोग करके प्राप्त किया जा सकता है. |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in/) | मान लंबाई (में) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz/) | मान एक आवृत्ति (kHz) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm/) | मान लंबाई (मिमी) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms/) | मान एक समय (मिलीसेकंड) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number/) | मान एक साधारण संख्या है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc/) | मान लंबाई (पीसी) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage/) | मान प्रतिशत है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt/) | मान लंबाई (पीटी) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px/) | मान लंबाई (पीएक्स) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad/) | मान एक कोण (रेड) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect/) | मान एक आयत कार्य है। GetRectValue पद्धति का उपयोग करके मान प्राप्त किया जा सकता है. |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem/) | मान लंबाई (रेम) है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | मान एक आरजीबी रंग है। GetRGBColorValue पद्धति का उपयोग करके मान प्राप्त किया जा सकता है. |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s/) | मान एक समय है। मूल्य getFloatValue विधि का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string/) | मान STRING है। मान getStringValue विधि का उपयोग करके प्राप्त किया जा सकता है. |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown/) | मान मान्यता प्राप्त CSS2 मान नहीं है। मूल्य केवल cssText विशेषता का उपयोग करके प्राप्त किया जा सकता है। |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri/) | मान एक यूआरआई है। मान getStringValue विधि का उपयोग करके प्राप्त किया जा सकता है. |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh/) | मान पूर्ण व्यूपोर्ट ऊंचाई का प्रतिशत है. |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax/) | मान व्यूपोर्ट की चौड़ाई या ऊंचाई का प्रतिशत होता है, जो भी बड़ा हो. |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin/) | मान व्यूपोर्ट की चौड़ाई या ऊंचाई का प्रतिशत है, जो भी छोटा हो. |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw/) | मान संपूर्ण व्यूपोर्ट चौड़ाई का प्रतिशत है. |

### यह सभी देखें

* class [CSSValue](../cssvalue/)
* नाम स्थान [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* सभा [Aspose.HTML](../../)


