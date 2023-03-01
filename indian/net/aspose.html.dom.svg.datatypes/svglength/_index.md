---
title: Class SVGLength
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength कक्ष. SVGLength इंटरफ़ेस मूल डेट प्रकर क लंबई से संबंधत है एक SVGLength ऑब्जेक्ट क केवल पढ़ने के लए नमत कय ज सकत है जसक अर्थ है क ऑब्जेक्ट क संशधत करने क प्रयस एक अपवद क फेंक देग जैस क नचे वर्णत है
type: docs
weight: 1200
url: /hi/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength इंटरफ़ेस मूल डेटा प्रकार की लंबाई से संबंधित है। एक SVGLength ऑब्जेक्ट को केवल पढ़ने के लिए नामित किया जा सकता है, जिसका अर्थ है कि ऑब्जेक्ट को संशोधित करने का प्रयास एक अपवाद को फेंक देगा, जैसा कि नीचे वर्णित है।

```csharp
public class SVGLength : SVGValueType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | इस इंटरफ़ेस पर परिभाषित SVG_LENGTHTYPE_* स्थिरांक में से एक द्वारा निर्दिष्ट मान का प्रकार। |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | उपयोगकर्ता इकाइयों में फ़्लोटिंग पॉइंट मान के रूप में मान। इस एट्रिब्यूट को सेट करने से valueInSpecifiedUnits और valueAsString इस सेटिंग को दिखाने के लिए अपने आप अपडेट हो जाएंगे. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | यूनिटटाइप द्वारा व्यक्त इकाइयों में एक स्ट्रिंग मान के रूप में मान। इस विशेषता को सेट करने से मान, valueInSpecifiedUnits और UnitType इस सेटिंग को दर्शाने के लिए अपने आप अपडेट हो जाएंगे. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | यूनिटटाइप द्वारा व्यक्त इकाइयों में फ्लोटिंग पॉइंट मान के रूप में मान। इस विशेषता को सेट करने से इस सेटिंग को दर्शाने के लिए मान और valueAsString अपने आप अपडेट हो जाएंगे. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | समान अंतर्निहित संग्रहीत मान को संरक्षित करें, लेकिन संग्रहीत इकाई पहचानकर्ता को दिए गए यूनिट टाइप पर रीसेट करें। इस विधि के परिणामस्वरूप ऑब्जेक्ट विशेषताएँ यूनिट टाइप, valueInSpecifiedUnits और valueAsString को संशोधित किया जा सकता है। उदाहरण के लिए, यदि मूल मान "0.5 सेमी" था और विधि को मिलीमीटर में बदलने के लिए लागू किया गया था, तो यूनिटटाइप को SVG_LENGTHTYPE_MM में बदल दिया जाएगा, valueInSpecifiedUnits को संख्यात्मक मान 5 में बदल दिया जाएगा और valueAsString को "5mm" में बदल दिया जाएगा। |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | संबंधित इकाई प्रकार के साथ मान को एक संख्या के रूप में रीसेट करें, जिससे ऑब्जेक्ट पर सभी विशेषताओं के मानों को बदल दिया जाए। |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | CSS2. में परिभाषित सेमी इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | CSS2. में परिभाषित em इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | CSS2. में परिभाषित पूर्व इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | CSS2. में परिभाषित इकाइयों में का उपयोग करके एक मान निर्दिष्ट किया गया था |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | CSS2. में परिभाषित मिमी इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | कोई इकाई प्रकार प्रदान नहीं किया गया था (यानी, एक इकाई रहित मान निर्दिष्ट किया गया था), जो उपयोगकर्ता इकाइयों में एक मान दर्शाता है। |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | CSS2. में परिभाषित पीसी इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | एक प्रतिशत मान निर्दिष्ट किया गया था। |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | CSS2. में परिभाषित पीटी इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | CSS2. में परिभाषित पीएक्स इकाइयों का उपयोग करके एक मान निर्दिष्ट किया गया था |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | इकाई प्रकार पूर्वनिर्धारित इकाई प्रकारों में से एक नहीं है। इस प्रकार के नए मान को परिभाषित करने का प्रयास करना या किसी मौजूदा मान को इस प्रकार में बदलने का प्रयास करना अमान्य है। |

### यह सभी देखें

* class [SVGValueType](../svgvaluetype/)
* नाम स्थान [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* सभा [Aspose.HTML](../../)


