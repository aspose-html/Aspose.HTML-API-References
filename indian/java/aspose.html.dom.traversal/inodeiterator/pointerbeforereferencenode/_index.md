---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "INodeIterator प्रॉपर्टी। इस फ़्लैग का मान निर्धारित करता है कि एंटिटी रेफ़रेंस नोड्स के चाइल्ड इटरेटर को दिखाई दें या नहीं। यदि false है तो वे और उनके वंशज अस्वीकार किए जाएंगे। ध्यान दें कि यह अस्वीकृति whatToShow और फ़िल्टर पर प्राथमिकता रखती है। यह वर्तमान में वह एकमात्र स्थिति है जहाँ NodeIterators पूर्ण सबट्री को अस्वीकार कर सकते हैं बजाय व्यक्तिगत नोड्स को स्किप करने के। दस्तावेज़ का वह दृश्य बनाने के लिए जहाँ एंटिटी रेफ़रेंस विस्तारित हैं और एंटिटी रेफ़रेंस नोड स्वयं उजागर नहीं होता, whatToShow फ़्लैग का उपयोग करके एंटिटी रेफ़रेंस नोड को छिपाएँ और इटरेटर बनाते समय expandEntityReferences को true सेट करें। दस्तावेज़ का वह दृश्य बनाने के लिए जहाँ एंटिटी रेफ़रेंस नोड्स हैं लेकिन कोई एंटिटी विस्तार नहीं है, whatToShow फ़्लैग का उपयोग करके एंटिटी रेफ़रेंस नोड को दिखाएँ और expandEntityReferences को false सेट करें।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

इस फ़्लैग का मान निर्धारित करता है कि एंटिटी रेफ़रेंस नोड्स के चाइल्ड इटरेटर को दिखाई दें या नहीं। यदि false है, तो वे और उनके वंशज अस्वीकार किए जाएंगे। ध्यान दें कि यह अस्वीकृति whatToShow और फ़िल्टर पर प्राथमिकता रखती है। यह वर्तमान में वह एकमात्र स्थिति है जहाँ NodeIterators पूर्ण सबट्री को अस्वीकार कर सकते हैं बजाय व्यक्तिगत नोड्स को स्किप करने के। दस्तावेज़ का वह दृश्य बनाने के लिए जहाँ एंटिटी रेफ़रेंस विस्तारित हैं और एंटिटी रेफ़रेंस नोड स्वयं उजागर नहीं होता, whatToShow फ़्लैग का उपयोग करके एंटिटी रेफ़रेंस नोड को छिपाएँ और इटरेटर बनाते समय expandEntityReferences को true सेट करें। दस्तावेज़ का वह दृश्य बनाने के लिए जहाँ एंटिटी रेफ़रेंस नोड्स हैं लेकिन कोई एंटिटी विस्तार नहीं है, whatToShow फ़्लैग का उपयोग करके एंटिटी रेफ़रेंस नोड को दिखाएँ और expandEntityReferences को false सेट करें।

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` यदि [expand entity references]; अन्यथा `false`.

### संबंधित देखें

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
