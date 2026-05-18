---
title: "Node.NodeName"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti Node. Properti read-only nodeName dari Node mengembalikan nama node saat ini sebagai String"
type: docs

url: /id/java/com.aspose.html.dom/node/nodename/
---
## Node.NodeName property

Properti read-only nodeName dari Node mengembalikan nama node saat ini sebagai String.

```java
public abstract String NodeName { get; }
```

### Property Value

Sebuah String, nilai untuk berbagai jenis node adalah:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The String "#cdata-section".[`Comment`](../../comment/) - The String "#comment".[`Document`](../../document/) - The String "#document".[`DocumentFragment`](../../documentfragment/) - The String "#document-fragment".[`DocumentType`](../../documenttype/) - The value of DocumentType.name[`Element`](../../element/) - The value of Element.tagName, that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like a SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of ProcessingInstruction.target[`Text`](../../text/) - The String "#text".

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-nodename](https://dom.spec.whatwg.org/#dom-node-nodename).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
