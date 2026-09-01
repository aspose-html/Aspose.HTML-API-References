---
title: "ITraversal Interface"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.traversal.ITraversal इंटरफ़ेस। इटरेटर का उपयोग नोड्स के सेट के माध्यम से कदम रखने के लिए किया जाता है, उदाहरण के लिए NodeList में नोड्स का सेट, किसी विशिष्ट नोड द्वारा नियंत्रित दस्तावेज़ उपवृक्ष, क्वेरी के परिणाम या कोई अन्य नोड सेट। इटरेट किए जाने वाले नोड्स का सेट NodeIterator के कार्यान्वयन द्वारा निर्धारित किया जाता है। DOM Level 2 दस्तावेज़ उपवृक्ष के दस्तावेज़-क्रम ट्रैवर्सल के लिए एकल NodeIterator कार्यान्वयन निर्दिष्ट करता है। इन इटरेटरों के उदाहरण DocumentTraversal .createNodeIterator को कॉल करके बनाए जाते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

इटरेटर्स का उपयोग नोड्स के सेट के माध्यम से कदम रखने के लिए किया जाता है, उदाहरण के लिए NodeList में नोड्स का सेट, किसी विशेष नोड द्वारा नियंत्रित दस्तावेज़ सबट्री, क्वेरी के परिणाम, या कोई अन्य नोड सेट। इटरेट किए जाने वाले नोड्स का सेट NodeIterator के इम्प्लीमेंटेशन द्वारा निर्धारित किया जाता है। DOM Level 2 दस्तावेज़ सबट्री के दस्तावेज़-क्रम ट्रैवर्सल के लिए एकल NodeIterator इम्प्लीमेंटेशन निर्दिष्ट करता है। इन इटरेटर्स के इंस्टेंस DocumentTraversal .createNodeIterator() को कॉल करके बनाए जाते हैं।

साथ ही देखें [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) नोड्स को स्क्रीन करने के लिए उपयोग किया जाने वाला NodeFilter। |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) NodeIterator का रूट नोड, जैसा कि निर्माण के समय निर्दिष्ट किया गया था। |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) यह गुण निर्धारित करता है कि कौन से नोड प्रकार इटरेटर के माध्यम से प्रस्तुत किए जाते हैं। उपलब्ध स्थिरांक सेट NodeFilter इंटरफ़ेस में परिभाषित है। whatToShow द्वारा अस्वीकार किए गए नोड्स को छोड़ दिया जाएगा, लेकिन उनके बच्चों को अभी भी माना जा सकता है। ध्यान दें कि यह स्किप किसी भी फ़िल्टर पर प्राथमिकता लेता है, यदि मौजूद हो। |

### संबंधित देखें

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
