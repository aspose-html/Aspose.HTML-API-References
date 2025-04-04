---
title: Node.NodeName
second_title: Aspose.HTML for .NET API Reference
description: Node NodeName property. The read-only nodeName property of Node returns the name of the current node as a string
type: docs
weight: 80
url: /net/aspose.html.dom/node/nodename/
---
## Node.NodeName property

The read-only nodeName property of Node returns the name of the current node as a string.

```csharp
public abstract string NodeName { get; }
```

### Property Value

A string, values for the different types of nodes are:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The string "#cdata-section".[`Comment`](../../comment/) - The string "#comment".[`Document`](../../document/) - The string "#document".[`DocumentFragment`](../../documentfragment/) - The string "#document-fragment".[`DocumentType`](../../documenttype/) - The value of DocumentType.name[`Element`](../../element/) - The value of Element.tagName, that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like a SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of ProcessingInstruction.target[`Text`](../../text/) - The string "#text".

## Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-nodename](https://dom.spec.whatwg.org/#dom-node-nodename).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### See Also

* class [Node](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
