---
title: "IDocumentCSS इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.IDocumentCSS इंटरफ़ेस। यह इंटरफ़ेस CSS दृश्य के साथ एक दस्तावेज़ का प्रतिनिधित्व करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

यह इंटरफ़ेस एक CSS दृश्य के साथ दस्तावेज़ का प्रतिनिधित्व करता है।

getOverrideStyle मेथड एक तंत्र प्रदान करता है जिसके माध्यम से DOM लेखक किसी तत्व की स्टाइल में तुरंत परिवर्तन कर सकता है बिना दस्तावेज़ की स्पष्ट रूप से लिंक की गई स्टाइल शीट्स या तत्वों की इनलाइन स्टाइल को संशोधित किए। यह स्टाइल शीट लेखक की स्टाइल शीट के बाद कास्केड एल्गोरिद्म में आती है और इसे ओवरराइड स्टाइल शीट कहा जाता है। ओवरराइड स्टाइल शीट लेखक की स्टाइल शीट्स पर प्राथमिकता रखती है। "!important" घोषणा अभी भी सामान्य घोषणा पर प्राथमिकता रखती है। ओवरराइड, लेखक, और उपयोगकर्ता स्टाइल शीट्स सभी में "!important" घोषणाएँ हो सकती हैं। उपयोगकर्ता की "!important" नियम ओवरराइड और लेखक की "!important" नियमों दोनों पर प्राथमिकता रखते हैं, और ओवरराइड की "!important" नियमें लेखक की "!important" नियमों पर प्राथमिकता रखती हैं।

अपेक्षा है कि DocumentCSS इंटरफ़ेस का एक उदाहरण Document इंटरफ़ेस के एक उदाहरण पर बाइंडिंग-विशिष्ट कास्टिंग मेथड्स का उपयोग करके प्राप्त किया जा सकता है।

इसके अलावा देखें [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)।

```java
public interface IDocumentCSS : IDocumentStyle
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | यह मेथड किसी निर्दिष्ट तत्व और किसी निर्दिष्ट pseudo-element के लिए ओवरराइड स्टाइल घोषणा को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |

### संबंधित देखें

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
