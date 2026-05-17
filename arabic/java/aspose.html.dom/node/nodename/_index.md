---
title: "Node.NodeName"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية Node. الخاصية nodeName للقراءة فقط في Node تُرجع اسم العقدة الحالية كسلسلة."
type: docs

url: /ar/java/com.aspose.html.dom/node/nodename/
---
## Node.NodeName property

الخاصية nodeName للقراءة فقط في Node تُرجع اسم العقدة الحالية كسلسلة.

```java
public abstract String NodeName { get; }
```

### Property Value

سلسلة، القيم لأنواع العقد المختلفة هي:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The String "#cdata-section".[`Comment`](../../comment/) - The String "#comment".[`Document`](../../document/) - The String "#document".[`DocumentFragment`](../../documentfragment/) - The String "#document-fragment".[`DocumentType`](../../documenttype/) - The value of DocumentType.name[`Element`](../../element/) - The value of Element.tagName, that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like a SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of ProcessingInstruction.target[`Text`](../../text/) - The String "#text".

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-nodename](https://dom.spec.whatwg.org/#dom-node-nodename).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
