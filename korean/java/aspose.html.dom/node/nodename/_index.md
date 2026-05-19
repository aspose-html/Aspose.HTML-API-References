---
title: "Node.NodeName"
second_title: "Aspose.HTML for Java API 참조"
description: "Node 속성. Node의 읽기 전용 nodeName 속성은 현재 노드의 이름을 문자열로 반환합니다"
type: docs

url: /ko/java/com.aspose.html.dom/node/nodename/
---
## Node.NodeName property

Node의 읽기 전용 nodeName 속성은 현재 노드의 이름을 문자열로 반환합니다.

```java
public abstract String NodeName { get; }
```

### Property Value

문자열이며, 다양한 노드 유형에 대한 값은 다음과 같습니다:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The String "#cdata-section".[`Comment`](../../comment/) - The String "#comment".[`Document`](../../document/) - The String "#document".[`DocumentFragment`](../../documentfragment/) - The String "#document-fragment".[`DocumentType`](../../documenttype/) - The value of DocumentType.name[`Element`](../../element/) - The value of Element.tagName, that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like a SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of ProcessingInstruction.target[`Text`](../../text/) - The String "#text".

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-nodename](https://dom.spec.whatwg.org/#dom-node-nodename).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
