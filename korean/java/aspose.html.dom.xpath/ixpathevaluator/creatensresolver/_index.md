---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Java용 Aspose.HTML API 참조"
description: "IXPathEvaluator method. 문서 내에서 나타난 노드의 컨텍스트에 상대적으로 XPath 식을 쉽게 평가할 수 있도록 패키지를 해결하도록 모든 DOM 노드를 조정합니다. 이 어댑터는 lookupNamespaceURI 메서드가 호출될 때 노드 계층 구조에 현재 제공된 정보를 사용하여 주어진 접두사로부터 packageURI를 해결하는 DOM Level 3의 lookupNamespaceURI 메서드와 같이 작동하며, 암시적 xml 접두사도 올바르게 해결합니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

문서 내에서 나타난 노드의 컨텍스트에 상대적으로 XPath 표현식을 쉽게 평가할 수 있도록 모든 DOM 노드를 패키지 해결에 맞게 변환합니다. 이 어댑터는 `lookupNamespaceURI` 메서드와 같이 작동하여, 호출 시 노드 계층 구조에 현재 존재하는 정보를 사용해 주어진 접두사에서 packageURI를 해결하고, 암시적 xml 접두사도 올바르게 해결합니다.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| nodeResolver | Node | 패키지 해석을 위한 컨텍스트로 사용될 노드입니다. |

### 반환 값

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### 또 보기

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
