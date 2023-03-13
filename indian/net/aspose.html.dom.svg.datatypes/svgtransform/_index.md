---
title: Class SVGTransform
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform कक्ष. SVGTransform एक SVGTransformList के भतर घटक परवर्तनं में से एक के लए इंटरफ़ेस है इस प्रकर एक SVGTransform ऑब्जेक्ट एक रूपंतरण वशेषत वनर्देश के भतर एक घटक उदहरण के लए स्केल ... य मैट्रक्स ... से मेल खत है
type: docs
weight: 1300
url: /hi/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform एक SVGTransformList के भीतर घटक परिवर्तनों में से एक के लिए इंटरफ़ेस है; इस प्रकार, एक SVGTransform ऑब्जेक्ट एक 'रूपांतरण' विशेषता विनिर्देश के भीतर एक घटक (उदाहरण के लिए, 'स्केल (...)' या 'मैट्रिक्स (...)') से मेल खाता है।

```csharp
public class SVGTransform : SVGValueType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX और SVG_TRANSFORM_SKEWY के लिए एक सुविधा विशेषता। यह निर्दिष्ट किया गया कोण रखता है। SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE और SVG_TRANSFORM_SCALE के लिए, कोण शून्य होगा। |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | मैट्रिक्स जो इस परिवर्तन का प्रतिनिधित्व करता है। मैट्रिक्स ऑब्जेक्ट लाइव है, जिसका अर्थ है कि SVGTransform ऑब्जेक्ट में किए गए कोई भी बदलाव मैट्रिक्स ऑब्जेक्ट में तुरंत परिलक्षित होते हैं और इसके विपरीत। यदि मैट्रिक्स ऑब्जेक्ट को सीधे बदल दिया जाता है (यानी, SVGTransform इंटरफ़ेस पर विधियों का उपयोग किए बिना) तो SVGTransform का प्रकार SVG_TRANSFORM_MATRIX. में बदल जाता है SVG_TRANSFORM_MATRIX के लिए, मैट्रिक्स में a, b, c, d, e, f होता है। उपयोगकर्ता द्वारा प्रदान किए गए मान। SVG_TRANSFORM_TRANSLATE के लिए, ई और एफ अनुवाद राशियों का प्रतिनिधित्व करते हैं (ए = 1, बी = 0, सी = 0 और डी = 1)। , c= 0, e= 0 और f = 0). SVG_TRANSFORM_SKEWX और SVG_TRANSFORM_SKEWY के लिए, a, b, c और d मैट्रिक्स का प्रतिनिधित्व करते हैं जिसके परिणामस्वरूप दिया गया तिरछा होगा (e= 0 और f = 0). SVG_TRANSFORM_ROTATE के लिए , ए, बी, सी, डी, ई और एफ एक साथ मैट्रिक्स का प्रतिनिधित्व करते हैं जिसके परिणामस्वरूप दिए गए रोटेशन होंगे। जब रोटेशन केंद्र बिंदु (0, 0) के आसपास होता है, तो ई और एफ शून्य होगा। |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | इस इंटरफ़ेस पर परिभाषित SVG_TRANSFORM_* स्थिरांक में से किसी एक द्वारा निर्दिष्ट मान का प्रकार। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_MATRIX पर सेट करता है, जिसमें पैरामीटर मैट्रिक्स नए ट्रांसफ़ॉर्मेशन को परिभाषित करता है। पैरामीटर मैट्रिक्स से मान कॉपी किए जाते हैं, मैट्रिक्स पैरामीटर SVGTransform::matrix. को प्रतिस्थापित नहीं करता है |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | रूपांतरण प्रकार को SVG_TRANSFORM_ROTATE पर सेट करता है, जिसमें पैरामीटर कोण रोटेशन कोण को परिभाषित करता है और पैरामीटर cx और cy रोटेशन के वैकल्पिक केंद्र को परिभाषित करता है। |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_SCALE पर सेट करता है, जिसमें पैरामीटर sx और sy स्केल राशियों को परिभाषित करते हैं। |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_SKEWX पर सेट करता है, पैरामीटर कोण तिरछापन की मात्रा को परिभाषित करता है। |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | परिवर्तन प्रकार को SVG_TRANSFORM_SKEWY पर सेट करता है, पैरामीटर कोण तिरछा की मात्रा को परिभाषित करता है। |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | रूपांतरण प्रकार को SVG_TRANSFORM_TRANSLATE पर सेट करता है, जिसमें पैरामीटर tx और ty अनुवाद राशियों को परिभाषित करते हैं। |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | एक 'मैट्रिक्स (...)' परिवर्तन। |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | एक 'घूर्णन (...)' परिवर्तन। |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | एक 'स्केल (...)' परिवर्तन। |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | एक 'तिरछा (...)' परिवर्तन। |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | एक 'तिरछा (...)' परिवर्तन। |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | एक 'अनुवाद (...)' परिवर्तन। |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | इकाई प्रकार पूर्वनिर्धारित प्रकारों में से एक नहीं है। इस प्रकार के नए मान को परिभाषित करने का प्रयास करना या किसी मौजूदा मान को इस प्रकार में बदलने का प्रयास करना अमान्य है। |

### यह सभी देखें

* class [SVGValueType](../svgvaluetype/)
* नाम स्थान [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* सभा [Aspose.HTML](../../)


