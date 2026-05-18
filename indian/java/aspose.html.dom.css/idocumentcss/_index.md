---
title: "IDocumentCSS इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.IDocumentCSS इंटरफ़ेस। यह इंटरफ़ेस एक दस्तावेज़ को CSS दृश्य के साथ दर्शाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

यह इंटरफ़ेस CSS दृश्य के साथ एक दस्तावेज़ का प्रतिनिधित्व करता है।

getOverrideStyle मेथड एक तंत्र प्रदान करता है जिसके द्वारा DOM लेखक किसी तत्व की स्टाइल में तुरंत परिवर्तन कर सकता है बिना दस्तावेज़ की स्पष्ट रूप से लिंक की गई स्टाइलशीट्स या स्टाइलशीट्स में तत्वों की इनलाइन स्टाइल को संशोधित किए। यह स्टाइलशीट कास्केड एल्गोरिद्म में लेखक की स्टाइलशीट के बाद आती है और इसे ओवरराइड स्टाइलशीट कहा जाता है। ओवरराइड स्टाइलशीट लेखक की स्टाइलशीट्स पर प्राथमिकता रखती है। एक "!important" घोषणा सामान्य घोषणा पर अभी भी प्राथमिकता रखती है। ओवरराइड, लेखक, और उपयोगकर्ता स्टाइलशीट्स सभी में "!important" घोषणाएँ हो सकती हैं। उपयोगकर्ता की "!important" नियम ओवरराइड और लेखक दोनों की "!important" नियमों पर प्राथमिकता रखते हैं, और ओवरराइड की "!important" नियम लेखक की "!important" नियमों पर प्राथमिकता रखती हैं।

अपेक्षा है कि DocumentCSS इंटरफ़ेस का एक उदाहरण Document इंटरफ़ेस के एक उदाहरण पर बाइंडिंग-विशिष्ट कास्टिंग मेथड्स का उपयोग करके प्राप्त किया जा सकता है।

इसके अलावा देखें [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)।

```java
public interface IDocumentCSS : IDocumentStyle
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | यह मेथड निर्दिष्ट तत्व और निर्दिष्ट प्यूडो-एलिमेंट के लिए ओवरराइड स्टाइल घोषणा को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |

### संबंधित देखें

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
