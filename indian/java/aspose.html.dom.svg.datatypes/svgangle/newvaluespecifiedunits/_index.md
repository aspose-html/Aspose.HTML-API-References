---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SVGAngle मेथड। मान को एक संख्या के रूप में रीसेट करें जिसमें संबंधित unitType हो, इस प्रकार ऑब्जेक्ट के सभी एट्रिब्यूट्स के मानों को बदल दिया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

मान को एक संख्या के रूप में रीसेट करें जिसमें संबंधित unitType हो, इस प्रकार ऑब्जेक्ट के सभी गुणों के मान बदल दिए जाते हैं।

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newUnitType | UInt16 | मान के लिए यूनिट टाइप (उदा., SVG_ANGLETYPE_DEG)। |
| valueInSpecifiedUnits | सिंगल | कोण का मान। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) उठाया जाता है यदि unitType SVG_ANGLETYPE_UNKNOWN है या वैध unit type स्थिरांक नहीं है (इंटरफ़ेस पर परिभाषित अन्य SVG_ANGLETYPE_* स्थिरांकों में से एक)। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) तब उठाया जाता है जब कोण एक केवल-पढ़ने योग्य एट्रिब्यूट से संबंधित होता है या जब स्वयं ऑब्जेक्ट केवल-पढ़ने योग्य हो। |

### संबंधित देखें

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
