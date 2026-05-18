---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "SVGLength मेथड। मान को एक संख्या के रूप में रीसेट करता है जिसमें संबंधित unitType हो, इस प्रकार ऑब्जेक्ट के सभी एट्रिब्यूट्स के मानों को बदल देता है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

मान को एक संख्या के रूप में रीसेट करें जिसमें संबंधित unitType हो, इस प्रकार ऑब्जेक्ट के सभी गुणों के मानों को बदल दिया जाता है।

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| unitType | UInt16 | मान के लिए इकाई प्रकार। |
| valueInSpecifiedUnits | Single | नया मान.. |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) उठाया जाता है यदि unitType SVG_LENGTHTYPE_UNKNOWN है या वैध unit type स्थिरांक नहीं है (इस इंटरफ़ेस पर परिभाषित अन्य SVG_LENGTHTYPE_* स्थिरांकों में से एक)। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) तब उठाया जाता है जब लंबाई केवल‑पढ़ने योग्य एट्रिब्यूट से मेल खाती है या जब ऑब्जेक्ट स्वयं केवल‑पढ़ने योग्य हो। |

### संबंधित देखें

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
