---
title: "Document.CreateElement"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Document मेथड। एक HTML दस्तावेज़ में document.createElement मेथड निर्दिष्ट tagName द्वारा HTML तत्व बनाता है या यदि tagName पहचाना नहीं जाता तो HTMLUnknownElement बनाता है"
type: docs

url: /hi/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

एक HTML दस्तावेज़ में, document.createElement() मेथड निर्दिष्ट tagName द्वारा HTML तत्व बनाता है, या यदि tagName पहचाना नहीं जाता तो एक [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) बनाता है।

```java
public Element CreateElement(String localName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | String | एक स्ट्रिंग जो बनाए जाने वाले तत्व के प्रकार को निर्दिष्ट करती है। बनाए गए तत्व का nodeName tagName के मान से प्रारंभ किया जाता है। इस मेथड के साथ योग्य नाम (जैसे "html:a") का उपयोग न करें। जब यह एक HTML दस्तावेज़ पर कॉल किया जाता है, तो createElement() तत्व बनाने से पहले tagName को लोअर केस में बदल देता है। |

### रिटर्न वैल्यू

नया [`Element`](../../element/).

## उदाहरण

```java
var element = document.CreateElement(tagName);
```

### संबंधित देखें

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
