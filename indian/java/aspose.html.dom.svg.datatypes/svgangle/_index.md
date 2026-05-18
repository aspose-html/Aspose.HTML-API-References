---
title: "SVGAngle क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle क्लास। SVGAngle इंटरफ़ेस कोण के बुनियादी डेटा प्रकार के अनुरूप है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

यह SVGAngle इंटरफ़ेस angle बुनियादी डेटा प्रकार के अनुरूप है।

```java
public class SVGAngle : SVGValueType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) मान का प्रकार, जैसा कि इस इंटरफ़ेस पर परिभाषित SVG_ANGLETYPE_* स्थिरांक में से एक द्वारा निर्दिष्ट किया गया है। |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | सहेजे गए मूल मान को समान रखें, लेकिन संग्रहीत इकाई पहचानकर्ता को दिए गए unitType पर रीसेट करें। ऑब्जेक्ट के गुण unitType, valueInSpecifiedUnits और valueAsString इस विधि के परिणामस्वरूप संशोधित हो सकते हैं। |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | मान को एक संख्या के रूप में रीसेट करें जिसमें संबंधित unitType हो, इस प्रकार ऑब्जेक्ट के सभी गुणों के मानों को बदल दिया जाता है। |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | इकाई प्रकार को स्पष्ट रूप से डिग्रीज़ पर सेट किया गया था। |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | इकाई प्रकार रैडियन है। |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | इकाई प्रकार रैडियन है। |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | इकाई प्रकार पूर्वनिर्धारित इकाई प्रकारों में से एक नहीं है। इस प्रकार का नया मान परिभाषित करने या मौजूदा मान को इस प्रकार में बदलने का प्रयास अवैध है। |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | कोई इकाई प्रकार प्रदान नहीं किया गया (अर्थात, एक इकाई‑रहित मान निर्दिष्ट किया गया)। कोणों के लिए, इकाई‑रहित मान को उसी तरह माना जाता है जैसे डिग्रीज़ निर्दिष्ट किए गए हों। |

### संबंधित देखें

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
