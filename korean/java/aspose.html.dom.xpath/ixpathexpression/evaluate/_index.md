---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.HTML for Java API 참조"
description: "IXPathExpression 메서드. 이 XPath 식을 평가하고 결과를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

이 XPath 식을 평가하고 결과를 반환합니다.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| contextNode | Node | `context`는 이 XPath 식을 평가하기 위한 컨텍스트 노드입니다. 만약 [`IXPathEvaluator`](../../ixpathevaluator/)를 [`Document`](../../../com.aspose.html.dom/document/)을 캐스팅하여 얻었다면, 이는 동일한 문서에 속해야 하며 [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), 또는 XPathNamespace 노드여야 합니다. 컨텍스트 노드가 [`Text`](../../../com.aspose.html.dom/text/) 또는 [`CDATASection`](../../../com.aspose.html.dom/cdatasection/)인 경우, 컨텍스트는 XPath가 보는 전체 논리 텍스트 노드로 해석되며, 노드가 비어 있는 경우 XPath 컨텍스트로 사용할 수 없습니다. |
| type | XPathResultType | 특정 `type`이 지정되면, 결과는 XPath 변환을 이용해 지정된 유형으로 강제 변환되어 반환되며, 원하는 강제 변환이 불가능할 경우 실패합니다. 이는 [`XPathResultType`](../../xpathresulttype/)의 값 중 하나여야 합니다. |
| result | Object | `result`는 이 메서드가 재사용하고 반환할 수 있는 특정 결과 객체를 지정합니다. `null`로 지정하거나 구현이 지정된 결과를 재사용하지 않으면 새 결과 객체가 생성되어 반환됩니다. XPath 1.0 결과의 경우, 이 객체는 [`IXPathResult`](../../ixpathresult/) 유형입니다. |

### 반환 값

XPath 식 평가의 결과입니다. XPath 1.0 결과의 경우, 이 객체는 [`IXPathResult`](../../ixpathresult/) 유형입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: 결과를 지정된 유형으로 변환할 수 없을 때 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: 노드가 이 [`IXPathExpression`](../)을 만든 [`IXPathEvaluator`](../../ixpathevaluator/)에서 지원하지 않는 문서에 속합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 노드가 XPath 컨텍스트 노드로 허용되는 유형이 아니거나 요청 유형이 이 [`IXPathExpression`](../)에 의해 허용되지 않습니다. |

### 또 보기

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
