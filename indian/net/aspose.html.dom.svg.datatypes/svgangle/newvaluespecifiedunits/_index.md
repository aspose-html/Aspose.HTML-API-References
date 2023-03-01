---
title: SVGAngle.NewValueSpecifiedUnits
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: SVGAngle तरक. संबंधत इकई प्रकर के सथ मन क एक संख्य के रूप में रसेट करें जससे ऑब्जेक्ट पर सभ वशेषतओं के मनं क बदल दय जए
type: docs
weight: 60
url: /hi/net/aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

संबंधित इकाई प्रकार के साथ मान को एक संख्या के रूप में रीसेट करें, जिससे ऑब्जेक्ट पर सभी विशेषताओं के मानों को बदल दिया जाए।

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newUnitType | UInt16 | मान के लिए इकाई प्रकार (उदा., SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | कोण मान। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | कोड[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) उठाया जाता है यदि यूनिट टाइप SVG_ANGLETYPE_UNKNOWN है या मान्य यूनिट प्रकार स्थिरांक नहीं है (इस इंटरफ़ेस पर परिभाषित अन्य SVG_ANGLETYPE_* स्थिरांक में से एक)। |
| [DOMException](../../../aspose.html.dom/domexception/) | कोड[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) उठाया जाता है जब कोण केवल पढ़ने के लिए विशेषता के अनुरूप होता है या जब ऑब्जेक्ट स्वयं ही पढ़ा जाता है। |

### यह सभी देखें

* class [SVGAngle](../)
* नाम स्थान [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* सभा [Aspose.HTML](../../../)


