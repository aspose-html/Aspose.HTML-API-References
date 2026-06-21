---
title: "Document.CreateNSResolver"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Document मेथड। किसी भी DOM नोड को पैकेज हल करने के लिए अनुकूलित करता है ताकि XPath अभिव्यक्ति को दस्तावेज़ के भीतर जहाँ वह नोड प्रकट हुआ है, उस नोड के संदर्भ के सापेक्ष आसानी से मूल्यांकन किया जा सके। यह एडेप्टर DOM Level 3 मेथड lookupNamespaceURI की तरह काम करता है, नोड्स पर दिए गए प्रीफ़िक्स से packageURI को हल करने के लिए, उस समय उपलब्ध नोड्स की पदानुक्रमित जानकारी का उपयोग करता है जब lookupNamespaceURI को कॉल किया जाता है, और साथ ही निहित xml प्रीफ़िक्स को भी सही ढंग से हल करता है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

किसी भी DOM नोड को पैकेजों को हल करने के लिए अनुकूलित करता है ताकि XPath अभिव्यक्ति को दस्तावेज़ में नोड के संदर्भ के सापेक्ष आसानी से मूल्यांकन किया जा सके। यह एडेप्टर DOM Level 3 मेथड `lookupNamespaceURI` की तरह काम करता है, जो नोड की पदानुक्रम में उपलब्ध वर्तमान जानकारी का उपयोग करके दिए गए प्रीफ़िक्स से packageURI को हल करता है, और xml प्रीफ़िक्स को भी सही ढंग से हल करता है।

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| nodeResolver | Node | पैकेज समाधान के लिए संदर्भ के रूप में उपयोग किए जाने वाले नोड। |

### रिटर्न वैल्यू

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### संबंधित देखें

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
