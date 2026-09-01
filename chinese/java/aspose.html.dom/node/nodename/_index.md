---
title: "Node.NodeName"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 属性。只读的 nodeName 属性（Node）返回当前节点的名称，类型为 String。"
type: docs

url: /zh/java/com.aspose.html.dom/node/nodename/
---
## Node.NodeName property

只读的 nodeName 属性（Node）返回当前节点的名称，类型为 String。

```java
public abstract String NodeName { get; }
```

### Property Value

一个 String，不同类型节点的取值如下：

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The String "#cdata-section".[`Comment`](../../comment/) - The String "#comment".[`Document`](../../document/) - The String "#document".[`DocumentFragment`](../../documentfragment/) - The String "#document-fragment".[`DocumentType`](../../documenttype/) - The value of DocumentType.name[`Element`](../../element/) - The value of Element.tagName, that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like a SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of ProcessingInstruction.target[`Text`](../../text/) - The String "#text".

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-nodename](https://dom.spec.whatwg.org/#dom-node-nodename).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
