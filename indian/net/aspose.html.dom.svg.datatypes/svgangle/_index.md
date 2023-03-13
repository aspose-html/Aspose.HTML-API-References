---
title: Class SVGAngle
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Svg.DataTypes.SVGAngle कक्ष. SVGAngle इंटरफ़ेस कण मूल डेट प्रकर से मेल खत है
type: docs
weight: 1060
url: /hi/net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle इंटरफ़ेस कोण मूल डेटा प्रकार से मेल खाता है।

```csharp
public class SVGAngle : SVGValueType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svgangle/unittype/) { get; } | इस इंटरफ़ेस पर परिभाषित SVG_ANGLETYPE_* स्थिरांक में से किसी एक द्वारा निर्दिष्ट मान का प्रकार। |
| [Value](../../aspose.html.dom.svg.datatypes/svgangle/value/) { get; set; } | फ़्लोटिंग पॉइंट मान के रूप में कोण मान, डिग्री में। इस एट्रिब्यूट को सेट करने से valueInSpecifiedUnits और valueAsString इस सेटिंग को दिखाने के लिए अपने आप अपडेट हो जाएंगे. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svgangle/valueasstring/) { get; set; } | यूनिट टाइप द्वारा व्यक्त इकाइयों में स्ट्रिंग मान के रूप में कोण मान। इस विशेषता को सेट करने से मान, valueInSpecifiedUnits और UnitType इस सेटिंग को दर्शाने के लिए अपने आप अपडेट हो जाएंगे. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | कोण मान फ्लोटिंग पॉइंट मान के रूप में, यूनिटटाइप द्वारा व्यक्त इकाइयों में। इस विशेषता को सेट करने से इस सेटिंग को दर्शाने के लिए मान और valueAsString अपने आप अपडेट हो जाएंगे. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | समान अंतर्निहित संग्रहीत मान को संरक्षित करें, लेकिन संग्रहीत इकाई पहचानकर्ता को दिए गए यूनिट टाइप पर रीसेट करें। ऑब्जेक्ट एट्रिब्यूट्स यूनिट टाइप, valueInSpecifiedUnits और valueAsString को इस विधि के परिणामस्वरूप संशोधित किया जा सकता है। |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | संबंधित इकाई प्रकार के साथ मान को एक संख्या के रूप में रीसेट करें, जिससे ऑब्जेक्ट पर सभी विशेषताओं के मानों को बदल दिया जाए। |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgangle/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | इकाई प्रकार स्पष्ट रूप से डिग्री पर सेट किया गया था। |
| const [SVG_ANGLETYPE_GRAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | इकाई प्रकार रेडियन है। |
| const [SVG_ANGLETYPE_RAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | इकाई प्रकार रेडियन है। |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | इकाई प्रकार पूर्वनिर्धारित इकाई प्रकारों में से एक नहीं है। इस प्रकार के नए मान को परिभाषित करने का प्रयास करना या किसी मौजूदा मान को इस प्रकार में बदलने का प्रयास करना अमान्य है। |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | कोई इकाई प्रकार प्रदान नहीं किया गया था (यानी, एक इकाई रहित मान निर्दिष्ट किया गया था)। कोणों के लिए, एक इकाई रहित मान को उसी तरह माना जाता है जैसे कि डिग्री निर्दिष्ट की गई थी। |

### यह सभी देखें

* class [SVGValueType](../svgvaluetype/)
* नाम स्थान [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* सभा [Aspose.HTML](../../)


