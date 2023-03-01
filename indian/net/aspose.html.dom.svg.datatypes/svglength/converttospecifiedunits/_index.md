---
title: SVGLength.ConvertToSpecifiedUnits
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: SVGLength तरक. समन अंतर्नहत संग्रहत मन क संरक्षत करें लेकन संग्रहत इकई पहचनकर्त क दए गए यूनट टइप पर रसेट करें इस वध के परणमस्वरूप ऑब्जेक्ट वशेषतएँ यूनट टइप valueInSpecifiedUnits और valueAsString क संशधत कय ज सकत है उदहरण के लए यद मूल मन 0.5 सेम थ और वध क मलमटर में बदलने के लए लगू कय गय थ त यूनटटइप क SVG_LENGTHTYPE_MM में बदल दय जएग valueInSpecifiedUnits क संख्यत्मक मन 5 में बदल दय जएग और valueAsString क 5mm में बदल दय जएग
type: docs
weight: 50
url: /hi/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

समान अंतर्निहित संग्रहीत मान को संरक्षित करें, लेकिन संग्रहीत इकाई पहचानकर्ता को दिए गए यूनिट टाइप पर रीसेट करें। इस विधि के परिणामस्वरूप ऑब्जेक्ट विशेषताएँ यूनिट टाइप, valueInSpecifiedUnits और valueAsString को संशोधित किया जा सकता है। उदाहरण के लिए, यदि मूल मान "0.5 सेमी" था और विधि को मिलीमीटर में बदलने के लिए लागू किया गया था, तो यूनिटटाइप को SVG_LENGTHTYPE_MM में बदल दिया जाएगा, valueInSpecifiedUnits को संख्यात्मक मान 5 में बदल दिया जाएगा और valueAsString को "5mm" में बदल दिया जाएगा।

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| unitType | UInt16 | स्विच करने के लिए इकाई प्रकार (उदा., SVG_LENGTHTYPE_MM). |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | कोड[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) उठाया जाता है यदि यूनिट टाइप SVG_LENGTHTYPE_UNKNOWN है या मान्य यूनिट प्रकार स्थिरांक नहीं है (इस इंटरफ़ेस पर परिभाषित अन्य SVG_LENGTHTYPE_* स्थिरांक में से एक)। |
| [DOMException](../../../aspose.html.dom/domexception/) | कोड[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) तब उठाया जाता है जब लंबाई केवल पढ़ने के लिए विशेषता से मेल खाती है या जब ऑब्जेक्ट स्वयं ही पढ़ा जाता है। |

### यह सभी देखें

* class [SVGLength](../)
* नाम स्थान [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* सभा [Aspose.HTML](../../../)


