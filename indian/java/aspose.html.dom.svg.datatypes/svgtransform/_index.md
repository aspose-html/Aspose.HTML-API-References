---
title: "SVGTransform क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform क्लास। SVGTransform एक इंटरफ़ेस है जो SVGTransformList के भीतर एक घटक परिवर्तन के लिए है, इसलिए एक SVGTransform ऑब्जेक्ट एकल घटक जैसे स्केल या मैट्रिक्स के अनुरूप होता है जो transform गुण विनिर्देश में होता है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform, SVGTransformList के भीतर एक घटक रूपांतरण के लिए इंटरफ़ेस है; इसलिए, एक SVGTransform ऑब्जेक्ट ‘transform’ विशेषता विनिर्देशन के भीतर एकल घटक (जैसे, 'scale(…)' या 'matrix(…)') से मेल खाता है।

```java
public class SVGTransform : SVGValueType
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX और SVG_TRANSFORM_SKEWY के लिए एक सुविधाजनक गुण। यह निर्दिष्ट किया गया कोण रखता है। SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE और SVG_TRANSFORM_SCALE के लिए, कोण शून्य होगा। |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) वह मैट्रिक्स जो इस परिवर्तन को दर्शाता है। मैट्रिक्स ऑब्जेक्ट लाइव है, अर्थात SVGTransform ऑब्जेक्ट में किए गए कोई भी परिवर्तन तुरंत मैट्रिक्स ऑब्जेक्ट में परिलक्षित होते हैं और इसके विपरीत। यदि मैट्रिक्स ऑब्जेक्ट को सीधे (अर्थात, SVGTransform इंटरफ़ेस की विधियों का उपयोग किए बिना) बदला जाता है तो SVGTransform का प्रकार SVG_TRANSFORM_MATRIX में बदल जाता है। SVG_TRANSFORM_MATRIX के लिए, मैट्रिक्स में उपयोगकर्ता द्वारा प्रदान किए गए a, b, c, d, e, f मान होते हैं। SVG_TRANSFORM_TRANSLATE के लिए, e और f अनुवाद मान दर्शाते हैं (a=1, b=0, c=0, d=1)। SVG_TRANSFORM_SCALE के लिए, a और d स्केल मान दर्शाते हैं (b=0, c=0, e=0, f=0)। SVG_TRANSFORM_SKEWX और SVG_TRANSFORM_SKEWY के लिए, a, b, c और d वह मैट्रिक्स दर्शाते हैं जो दिए गए स्क्यू (e=0 और f=0) का परिणाम देगा। SVG_TRANSFORM_ROTATE के लिए, a, b, c, d, e और f मिलकर वह मैट्रिक्स बनाते हैं जो दिए गए घूर्णन का परिणाम देगा। जब घूर्णन केंद्र बिंदु (0, 0) के चारों ओर होता है, तो e और f शून्य होंगे। |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) मान का प्रकार जैसा कि इस इंटरफ़ेस पर परिभाषित SVG_TRANSFORM_* स्थिरांक में से एक द्वारा निर्दिष्ट किया गया है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अनमैनेज्ड और - वैकल्पिक रूप से - मैनेज्ड रिसोर्सेज़ को रिलीज़ करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_MATRIX पर सेट करता है, जिसमें पैरामीटर matrix नई परिवर्तन को परिभाषित करता है। पैरामीटर matrix से मान कॉपी किए जाते हैं, matrix पैरामीटर SVGTransform::matrix को प्रतिस्थापित नहीं करता। |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_ROTATE पर सेट करता है, जिसमें पैरामीटर angle घूर्णन कोण को परिभाषित करता है और पैरामीटर cx और cy वैकल्पिक घूर्णन केंद्र को परिभाषित करते हैं। |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_SCALE पर सेट करता है, जिसमें पैरामीटर sx और sy स्केल मानों को परिभाषित करते हैं। |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_SKEWX पर सेट करता है, जिसमें पैरामीटर angle स्क्यू की मात्रा को परिभाषित करता है। |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_SKEWY पर सेट करता है, जिसमें पैरामीटर angle स्क्यू की मात्रा को परिभाषित करता है। |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | ट्रांसफ़ॉर्म प्रकार को SVG_TRANSFORM_TRANSLATE पर सेट करता है, जिसमें पैरामीटर tx और ty अनुवाद मानों को परिभाषित करते हैं। |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | 'matrix(…)' परिवर्तन। |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | 'rotate(…)' परिवर्तन। |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | एक 'scale(…)' रूपांतरण। |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | एक 'skewX(…)' रूपांतरण। |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | एक 'skewY(…)' रूपांतरण। |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | एक 'translate(…)' रूपांतरण। |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | यूनिट प्रकार पूर्वनिर्धारित प्रकारों में से एक नहीं है। इस प्रकार का नया मान परिभाषित करने या मौजूदा मान को इस प्रकार में बदलने का प्रयास करना अवैध है। |

### संबंधित देखें

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
