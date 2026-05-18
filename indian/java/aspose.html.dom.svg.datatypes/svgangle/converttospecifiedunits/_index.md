---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "SVGAngle मेथड। समान अंतर्निहित संग्रहीत मान को बनाए रखें लेकिन संग्रहीत unit पहचानकर्ता को दिए गए unitType पर रीसेट करें। इस मेथड के परिणामस्वरूप ऑब्जेक्ट एट्रिब्यूट्स unitType, valueInSpecifiedUnits और valueAsString संशोधित हो सकते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

सहेजे गए मूल मान को समान रखें, लेकिन संग्रहीत इकाई पहचानकर्ता को दिए गए unitType पर रीसेट करें। ऑब्जेक्ट के गुण unitType, valueInSpecifiedUnits और valueAsString इस विधि के परिणामस्वरूप संशोधित हो सकते हैं।

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| unitType | UInt16 | स्विच करने के लिए unit type (उदा., SVG_ANGLETYPE_DEG)। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)उठाया जाता है यदि unitType SVG_ANGLETYPE_UNKNOWN है या वैध unit type स्थिरांक नहीं है (इस इंटरफ़ेस पर परिभाषित अन्य SVG_ANGLETYPE_* स्थिरांकों में से एक)। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) तब उठाया जाता है जब कोण एक केवल-पढ़ने योग्य एट्रीब्यूट से संबंधित होता है या जब ऑब्जेक्ट स्वयं केवल-पढ़ने योग्य होता है। |

### संबंधित देखें

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
