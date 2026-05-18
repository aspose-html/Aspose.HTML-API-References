---
title: "INodeIterator इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.traversal.INodeIterator इंटरफ़ेस। इटरेटर का उपयोग नोड्स के सेट के माध्यम से कदम रखने के लिए किया जाता है, उदाहरण के लिए NodeList में नोड्स का सेट, किसी विशेष नोड द्वारा नियंत्रित दस्तावेज़ उपवृक्ष, क्वेरी के परिणाम या कोई अन्य नोड सेट। इटरेट किए जाने वाले नोड्स का सेट NodeIterator के कार्यान्वयन द्वारा निर्धारित होता है। DOM Level 2 दस्तावेज़‑क्रम ट्रैवर्सल के लिए एकल NodeIterator कार्यान्वयन निर्दिष्ट करता है। इन इटरेटरों के उदाहरण DocumentTraversal.createNodeIterator को कॉल करके बनाए जाते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

इटरेटर का उपयोग नोड्स के सेट के माध्यम से कदम रखने के लिए किया जाता है, उदाहरण के लिए NodeList में नोड्स का सेट, किसी विशेष नोड द्वारा नियंत्रित दस्तावेज़ सबट्री, किसी क्वेरी के परिणाम, या किसी अन्य नोड्स के सेट। इटरेट किए जाने वाले नोड्स का सेट NodeIterator के कार्यान्वयन द्वारा निर्धारित होता है। DOM Level 2 दस्तावेज़‑क्रम ट्रैवर्सल के लिए एकल NodeIterator कार्यान्वयन निर्दिष्ट करता है। इन इटरेटर्स के उदाहरण DocumentTraversal .createNodeIterator() को कॉल करके बनाए जाते हैं।

इसके अलावा देखें [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)। @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) इस फ़्लैग का मान निर्धारित करता है कि एंटिटी रेफ़रेंस नोड्स के बच्चे इटरेटर के लिए दृश्यमान हैं या नहीं। यदि false है, तो वे और उनके वंशज अस्वीकार कर दिए जाएंगे। ध्यान दें कि यह अस्वीकृति whatToShow और फ़िल्टर पर प्राथमिकता रखती है। यह भी ध्यान दें कि वर्तमान में यह एकमात्र स्थिति है जहाँ NodeIterators पूर्ण उपवृक्ष को अस्वीकार कर सकते हैं, बजाय व्यक्तिगत नोड्स को छोड़ने के। दस्तावेज़ का वह दृश्य बनाने के लिए जिसमें एंटिटी रेफ़रेंसेज़ विस्तारित हों और एंटिटी रेफ़रेंस नोड स्वयं उजागर न हो, whatToShow फ़्लैग का उपयोग करके एंटिटी रेफ़रेंस नोड को छिपाएँ और इटरेटर बनाते समय expandEntityReferences को true सेट करें। दस्तावेज़ का वह दृश्य बनाने के लिए जिसमें एंटिटी रेफ़रेंस नोड्स हों लेकिन एंटिटी विस्तार न हो, whatToShow फ़्लैग का उपयोग करके एंटिटी रेफ़रेंस नोड दिखाएँ और expandEntityReferences को false सेट करें। |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) वर्तमान रेफ़रेंस नोड। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | NodeIterator को उस सेट से अलग करता है जिस पर वह इटरेट कर रहा था, किसी भी गणनात्मक संसाधनों को मुक्त करता है और इटरेटर को INVALID स्थिति में रखता है। डिटैच को बुलाने के बाद, nextNode या previousNode को कॉल करने पर INVALID_STATE_ERR अपवाद उत्पन्न होगा। |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | सेट में अगला नोड लौटाता है और सेट में इटरेटर की स्थिति को आगे बढ़ाता है। एक NodeIterator बनाने के बाद, nextNode() का पहला कॉल सेट में पहला नोड लौटाता है। |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | सेट में पिछला नोड लौटाता है और सेट में NodeIterator की स्थिति को पीछे की ओर ले जाता है। |

### संबंधित देखें

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
