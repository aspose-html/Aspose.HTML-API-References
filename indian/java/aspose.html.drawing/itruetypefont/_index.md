---
title: "ITrueTypeFont इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.drawing.ITrueTypeFont इंटरफ़ेस। TrueType फ़ॉन्ट के साथ काम करने के लिए मेथड्स घोषित करता है"
type: docs

url: /hi/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

TrueType फ़ॉन्ट के साथ काम करने के लिए विधियों को घोषित करता है।

```java
public interface ITrueTypeFont
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) फ़ॉन्ट डेटा का आकार बाइट्स में लौटाता है |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) फ़ॉन्ट परिवार का नाम प्राप्त करें। |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) यह "FamilyName" और "SubFamilyName" का संयोजन होना चाहिए। अपवाद: यदि फ़ॉन्ट "SubFamilyName" में "Regular" के रूप में दर्शाया गया है, तो केवल "FamilyName" में मौजूद परिवार नाम का उपयोग करें। ऊपर दी गई पूर्ण फ़ॉन्ट नाम की परिभाषा का एक अपवाद Microsoft प्लेटफ़ॉर्म स्ट्रिंग्स के लिए CFF OpenType फ़ॉन्ट्स में है: इस मामले में, पूर्ण फ़ॉन्ट नाम स्ट्रिंग CFF Name INDEX में PostScript FontName के समान होना चाहिए। |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) फ़ॉन्ट सबफ़ैमिली नाम समान फ़ॉन्ट फ़ैमिली नाम वाले समूह में फ़ॉन्ट को अलग करता है। इसे शैली (इटैलिक, ऑब्लिक) और वजन (लाइट, बोल्ड, ब्लैक आदि) को दर्शाने के लिए माना जाता है। वजन या शैली में कोई विशेष अंतर न रखने वाले फ़ॉन्ट (उदा. मध्यम वजन, इटैलिक नहीं और fsSelection बिट 6 सेट) को इस स्थिति में स्ट्रिंग "Regular" संग्रहीत करनी चाहिए। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | असेंट को पॉइंट्स में लौटाता है। |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | फ़ॉन्ट डेटा के साथ स्ट्रीम खोलें। कॉलर स्ट्रीम को डिस्पोज़ करने के लिए जिम्मेदार है। |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | डिसेंट को पॉइंट्स में लौटाता है। |

### संबंधित देखें

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
