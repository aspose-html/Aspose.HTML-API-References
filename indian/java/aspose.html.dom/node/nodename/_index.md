---
title: "Node.NodeName"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Node प्रॉपर्टी। पढ़ने‑के‑लिए‑केवल nodeName प्रॉपर्टी Node का वर्तमान नोड का नाम स्ट्रिंग के रूप में लौटाती है।"
type: docs

url: /hi/java/com.aspose.html.dom/node/nodename/
---
## Node.NodeName property

पढ़ने‑के‑लिए‑केवल nodeName प्रॉपर्टी Node का वर्तमान नोड का नाम स्ट्रिंग के रूप में लौटाती है।

```java
public abstract String NodeName { get; }
```

### Property Value

एक स्ट्रिंग, विभिन्न प्रकार के नोड्स के मान इस प्रकार हैं:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The String "#cdata-section".[`Comment`](../../comment/) - The String "#comment".[`Document`](../../document/) - The String "#document".[`DocumentFragment`](../../documentfragment/) - The String "#document-fragment".[`DocumentType`](../../documenttype/) - The value of DocumentType.name[`Element`](../../element/) - The value of Element.tagName, that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like a SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of ProcessingInstruction.target[`Text`](../../text/) - The String "#text".

## टिप्पणियाँ

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-nodename](https://dom.spec.whatwg.org/#dom-node-nodename).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
