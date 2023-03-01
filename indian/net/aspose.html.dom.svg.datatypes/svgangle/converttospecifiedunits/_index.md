---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: SVGAngle तरक. समन अंतर्नहत संग्रहत मन क संरक्षत करें लेकन संग्रहत इकई पहचनकर्त क दए गए यूनट टइप पर रसेट करें ऑब्जेक्ट एट्रब्यूट्स यूनट टइप valueInSpecifiedUnits और valueAsString क इस वध के परणमस्वरूप संशधत कय ज सकत है
type: docs
weight: 50
url: /hi/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

समान अंतर्निहित संग्रहीत मान को संरक्षित करें, लेकिन संग्रहीत इकाई पहचानकर्ता को दिए गए यूनिट टाइप पर रीसेट करें। ऑब्जेक्ट एट्रिब्यूट्स यूनिट टाइप, valueInSpecifiedUnits और valueAsString को इस विधि के परिणामस्वरूप संशोधित किया जा सकता है।

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| unitType | UInt16 | स्विच करने के लिए यूनिट का प्रकार (उदाहरण के लिए, SVG_ANGLETYPE_DEG)। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | कोड[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) उठाया जाता है यदि यूनिट टाइप SVG_ANGLETYPE_UNKNOWN है या मान्य यूनिट प्रकार स्थिरांक नहीं है (इस इंटरफ़ेस पर परिभाषित अन्य SVG_ANGLETYPE_* स्थिरांक में से एक)। |
| [DOMException](../../../aspose.html.dom/domexception/) | कोड[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) उठाया जाता है जब कोण केवल पढ़ने के लिए विशेषता के अनुरूप होता है या जब ऑब्जेक्ट स्वयं ही पढ़ा जाता है। |

### यह सभी देखें

* class [SVGAngle](../)
* नाम स्थान [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* सभा [Aspose.HTML](../../../)


