---
title: "Node.TextContent"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Node प्रॉपर्टी। Node इंटरफ़ेस की textContent प्रॉपर्टी नोड और उसके वंशजों की पाठ सामग्री को दर्शाती है"
type: docs

url: /hi/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

[`Node`](../) इंटरफ़ेस की textContent प्रॉपर्टी नोड और उसके वंशजों की पाठ सामग्री को दर्शाती है।

```java
public String TextContent { get; set; }
```

### Property Value

एक स्ट्रिंग, या null। इसका मान स्थिति पर निर्भर करता है:

यदि नोड एक दस्तावेज़ या डॉctype है, तो textContent null लौटाता है। नोट: पूरे दस्तावेज़ के सभी टेक्स्ट और CDATA डेटा प्राप्त करने के लिए, document.documentElement.textContent का उपयोग करें। यदि नोड एक CDATA सेक्शन, टिप्पणी, प्रोसेसिंग इंस्ट्रक्शन, या टेक्स्ट नोड है, तो textContent नोड के भीतर का टेक्स्ट लौटाता है या सेट करता है, अर्थात् [`Node.nodeValue`](../nodevalue/)। अन्य नोड प्रकारों के लिए, textContent प्रत्येक चाइल्ड नोड के textContent को जोड़ता है, जिसमें टिप्पणियाँ और प्रोसेसिंग इंस्ट्रक्शन शामिल नहीं होते।

## टिप्पणियाँ

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
