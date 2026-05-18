---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "SVGLength मेथड। समान अंतर्निहित संग्रहीत मान को बनाए रखें लेकिन संग्रहीत यूनिट पहचानकर्ता को दिए गए unitType पर रीसेट करें। इस मेथड के परिणामस्वरूप ऑब्जेक्ट एट्रिब्यूट्स unitType, valueInSpecifiedUnits और valueAsString संशोधित हो सकते हैं। उदाहरण के लिए यदि मूल मान 0.5cm था और मेथड को मिलीमीटर में बदलने के लिए बुलाया गया, तो unitType को SVG_LENGTHTYPE_MM में बदल दिया जाएगा, valueInSpecifiedUnits को संख्यात्मक मान 5 में बदल दिया जाएगा और valueAsString को 5mm में बदल दिया जाएगा।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

एक ही अंतर्निहित संग्रहीत मान को बनाए रखें, लेकिन संग्रहीत इकाई पहचानकर्ता को दिए गए unitType पर रीसेट करें। इस विधि के परिणामस्वरूप ऑब्जेक्ट गुण unitType, valueInSpecifiedUnits और valueAsString संशोधित हो सकते हैं। उदाहरण के लिए, यदि मूल मान "0.5cm" था और विधि को मिलीमीटर में बदलने के लिए बुलाया गया, तो unitType को SVG_LENGTHTYPE_MM में बदल दिया जाएगा, valueInSpecifiedUnits को संख्यात्मक मान 5 में बदल दिया जाएगा और valueAsString को "5mm" में बदल दिया जाएगा।

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| unitType | UInt16 | स्विच करने के लिए यूनिट टाइप (उदाहरण के लिए, SVG_LENGTHTYPE_MM)। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) उठाया जाता है यदि unitType SVG_LENGTHTYPE_UNKNOWN है या वैध unit type स्थिरांक नहीं है (इस इंटरफ़ेस पर परिभाषित अन्य SVG_LENGTHTYPE_* स्थिरांकों में से एक)। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) तब उठाया जाता है जब लंबाई केवल‑पढ़ने योग्य एट्रिब्यूट से मेल खाती है या जब ऑब्जेक्ट स्वयं केवल‑पढ़ने योग्य हो। |

### संबंधित देखें

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
