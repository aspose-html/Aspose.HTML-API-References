---
title: Interface ITrueTypeFont
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Drawing.ITrueTypeFont इंटरफेस. ट्रू टइप फ़न्ट के सथ कम करने के तरकं क घषण करत है.
type: docs
weight: 2760
url: /hi/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

ट्रू टाइप फ़ॉन्ट के साथ काम करने के तरीकों की घोषणा करता है.

```csharp
public interface ITrueTypeFont
```

## गुण

| नाम | विवरण |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | बाइट्स में फ़ॉन्ट डेटा का आकार लौटाता है |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | फ़ॉन्ट परिवार का नाम प्राप्त करें। |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | यह "FamilyName" और "SubFamilyName" का संयोजन होना चाहिए। अपवाद: यदि फ़ॉन्ट "नियमित" है जैसा कि "SubFamilyName" में इंगित किया गया है, तो केवल "FamilyName" में निहित पारिवारिक नाम का उपयोग करें। पूर्ण फ़ॉन्ट नाम की उपरोक्त परिभाषा का एक अपवाद Microsoft प्लेटफ़ॉर्म स्ट्रिंग्स के लिए है CFF ओपन टाइप फ़ॉन्ट्स के लिए: इस मामले में, पूर्ण फ़ॉन्ट नाम स्ट्रिंग CFF नाम INDEX. में पोस्टस्क्रिप्ट फ़ॉन्टनाम के समान होना चाहिए। |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | फ़ॉन्ट सबफ़ैमिली नाम एक ही फ़ॉन्ट परिवार नाम वाले समूह में फ़ॉन्ट को अलग करता है। यह शैली (इटैलिक, तिरछा) और वजन (हल्का, बोल्ड, काला, आदि) को संबोधित करने के लिए माना जाता है। एक फ़ॉन्ट जिसमें वजन या शैली में कोई विशेष अंतर नहीं है (उदाहरण के लिए मध्यम वजन, इटैलिक नहीं और fsSelection बिट 6 सेट) में स्ट्रिंग "नियमित" इस स्थिति में संग्रहीत होनी चाहिए। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | अंक में चढ़ाई लौटाता है। |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | स्ट्रीम को फ़ॉन्ट डेटा के साथ खोलें। कॉलर स्ट्रीम को निपटाने के लिए जिम्मेदार है। |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | डिसेंट को पॉइंट्स में लौटाता है। |

### यह सभी देखें

* नाम स्थान [Aspose.Html.Drawing](../../aspose.html.drawing/)
* सभा [Aspose.HTML](../../)


