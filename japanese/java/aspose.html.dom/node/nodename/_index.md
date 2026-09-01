---
title: "Node.NodeName"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node プロパティ。Node の読み取り専用 nodeName プロパティは、現在のノードの名前を文字列として返します"
type: docs

url: /ja/java/com.aspose.html.dom/node/nodename/
---
## Node.NodeName property

Node の読み取り専用 nodeName プロパティは、現在のノードの名前を文字列として返します。

```java
public abstract String NodeName { get; }
```

### Property Value

文字列で、さまざまなノードタイプの値は次のとおりです：

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The String "#cdata-section".[`Comment`](../../comment/) - The String "#comment".[`Document`](../../document/) - The String "#document".[`DocumentFragment`](../../documentfragment/) - The String "#document-fragment".[`DocumentType`](../../documenttype/) - The value of DocumentType.name[`Element`](../../element/) - The value of Element.tagName, that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like a SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of ProcessingInstruction.target[`Text`](../../text/) - The String "#text".

## 備考

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-nodename](https://dom.spec.whatwg.org/#dom-node-nodename).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
