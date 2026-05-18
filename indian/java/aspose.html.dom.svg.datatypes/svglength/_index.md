---
title: "SVGLength क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.svg.datatypes.SVGLength क्लास। SVGLength इंटरफ़ेस लंबाई के बुनियादी डेटा प्रकार से मेल खाता है। एक SVGLength ऑब्जेक्ट को केवल-पढ़ने योग्य के रूप में निर्धारित किया जा सकता है, जिसका अर्थ है कि ऑब्जेक्ट को संशोधित करने के प्रयास नीचे वर्णित अनुसार एक अपवाद उत्पन्न करेंगे"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength इंटरफ़ेस लंबाई मूल डेटा प्रकार से मेल खाता है। एक SVGLength ऑब्जेक्ट को केवल-पढ़ने योग्य निर्धारित किया जा सकता है, जिसका अर्थ है कि ऑब्जेक्ट को संशोधित करने के प्रयास से नीचे वर्णित अनुसार एक अपवाद उत्पन्न होगा।

```java
public class SVGLength : SVGValueType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) इस इंटरफ़ेस पर परिभाषित SVG_LENGTHTYPE_* स्थिरांकों में से एक द्वारा निर्दिष्ट मान का प्रकार। |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | एक ही अंतर्निहित संग्रहीत मान को बनाए रखें, लेकिन संग्रहीत इकाई पहचानकर्ता को दिए गए unitType पर रीसेट करें। इस विधि के परिणामस्वरूप ऑब्जेक्ट गुण unitType, valueInSpecifiedUnits और valueAsString संशोधित हो सकते हैं। उदाहरण के लिए, यदि मूल मान "0.5cm" था और विधि को मिलीमीटर में बदलने के लिए बुलाया गया, तो unitType को SVG_LENGTHTYPE_MM में बदल दिया जाएगा, valueInSpecifiedUnits को संख्यात्मक मान 5 में बदल दिया जाएगा और valueAsString को "5mm" में बदल दिया जाएगा। |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | मान को एक संख्या के रूप में रीसेट करें जिसमें संबंधित unitType हो, इस प्रकार ऑब्जेक्ट के सभी गुणों के मानों को बदल दिया जाता है। |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | CSS2 में परिभाषित cm इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | CSS2 में परिभाषित em इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | CSS2 में परिभाषित ex इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | CSS2 में परिभाषित in इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | CSS2 में परिभाषित mm इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | कोई इकाई प्रकार प्रदान नहीं किया गया (अर्थात, एक बिना इकाई वाला मान निर्दिष्ट किया गया), जो उपयोगकर्ता इकाइयों में मान को दर्शाता है। |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | CSS2 में परिभाषित pc इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | एक प्रतिशत मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | CSS2 में परिभाषित pt इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | CSS2 में परिभाषित px इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | इकाई प्रकार पूर्वनिर्धारित इकाई प्रकारों में से एक नहीं है। इस प्रकार का नया मान परिभाषित करने या मौजूदा मान को इस प्रकार में बदलने का प्रयास अवैध है। |

### संबंधित देखें

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
