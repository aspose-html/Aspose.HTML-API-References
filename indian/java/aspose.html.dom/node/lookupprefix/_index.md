---
title: "Node.LookupPrefix"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Node मेथड। Node इंटरफ़ेस का lookupPrefix मेथड एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स होता है यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों तो पहला प्रीफ़िक्स लौटाया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

lookupPrefix() मेथड Node इंटरफ़ेस का एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स शामिल होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है।

```java
public String LookupPrefix(String packageURI)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| packageURI | String | एक स्ट्रिंग जिसमें पैकेज के लिए प्रीफ़िक्स खोजने की जानकारी होती है। |

### रिटर्न वैल्यू

एक स्ट्रिंग जिसमें संबंधित प्रीफ़िक्स होता है, या यदि कोई नहीं मिला तो null। यदि पैकेज null है, या खाली स्ट्रिंग है, तो lookupPrefix() null लौटाता है।

यदि नोड एक [`DocumentType`](../../documenttype/) या एक [`DocumentFragment`](../../documentfragment/) है, तो lookupPrefix() हमेशा null लौटाता है।

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
