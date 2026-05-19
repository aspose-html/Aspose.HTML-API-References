---
title: "Document.CreateNSResolver"
second_title: "Aspose.HTML for Java API 참조"
description: "Document 메서드. DOM 노드를 패키지를 해결하도록 조정하여 XPath 식을 문서 내에서 해당 노드가 나타난 컨텍스트를 기준으로 쉽게 평가할 수 있게 합니다. 이 어댑터는 lookupNamespaceURI 메서드와 같이 동작하여, 호출 시점에 노드 계층 구조에 존재하는 현재 정보를 사용해 주어진 접두사로부터 packageURI를 해결하고, 암시적인 xml 접두사도 올바르게 해결합니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

문서 내에서 나타난 노드의 컨텍스트를 기준으로 XPath 표현식을 쉽게 평가할 수 있도록 모든 DOM 노드를 패키지 해결에 맞게 변환합니다. 이 어댑터는 `lookupNamespaceURI` 메서드와 유사하게 동작하여, 호출 시점에 노드 계층 구조에 존재하는 현재 정보를 사용해 주어진 접두사로부터 packageURI를 해결하고, 암시적인 xml 접두사도 올바르게 해결합니다.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nodeResolver | Node | 패키지 해석을 위한 컨텍스트로 사용할 노드입니다. |

### 반환 값

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### 또 보기

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
