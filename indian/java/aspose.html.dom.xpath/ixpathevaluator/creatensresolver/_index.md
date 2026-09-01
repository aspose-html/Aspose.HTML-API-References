---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IXPathEvaluator method. किसी भी DOM नोड को पैकेज हल करने के लिए अनुकूलित करता है ताकि XPath अभिव्यक्ति को दस्तावेज़ में नोड के संदर्भ के सापेक्ष आसानी से मूल्यांकन किया जा सके। यह एडेप्टर DOM Level 3 की विधि lookupNamespaceURI की तरह काम करता है, नोड्स की पदानुक्रम में उपलब्ध वर्तमान जानकारी का उपयोग करके दिए गए उपसर्ग से packageURI को हल करता है, और lookupNamespaceURI कॉल होने के समय निहित xml उपसर्ग को भी सही ढंग से हल करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

किसी भी DOM नोड को पैकेजों को हल करने के लिए अनुकूलित करता है ताकि XPath अभिव्यक्ति को दस्तावेज़ में नोड के संदर्भ के सापेक्ष आसानी से मूल्यांकन किया जा सके। यह एडेप्टर DOM Level 3 मेथड `lookupNamespaceURI` की तरह काम करता है, जो नोड की पदानुक्रम में उपलब्ध वर्तमान जानकारी का उपयोग करके दिए गए प्रीफ़िक्स से packageURI को हल करता है, और xml प्रीफ़िक्स को भी सही ढंग से हल करता है।

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| nodeResolver | Node | पैकेज समाधान के लिए संदर्भ के रूप में उपयोग किए जाने वाले नोड। |

### रिटर्न वैल्यू

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### संबंधित देखें

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
