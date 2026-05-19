---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.HTML for Java API 참조"
description: "IXPathEvaluator 메서드. XPath 식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

XPath 표현식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 식 | String | 파싱 및 평가할 XPath 식 문자열입니다. |
| contextNode | Node | `context`는 이 XPath 식을 평가하기 위한 컨텍스트 노드입니다. 만약 [`IXPathEvaluator`](../)가 [`Document`](../../../com.aspose.html.dom/document/)을 캐스팅하여 얻어진 경우, 이 노드는 동일한 문서에 속해야 하며 [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) 또는 XPathNamespace 노드여야 합니다. 컨텍스트 노드가 [`Text`](../../../com.aspose.html.dom/text/) 또는 [`CDATASection`](../../../com.aspose.html.dom/cdatasection/)인 경우, 해당 컨텍스트는 XPath이 보는 전체 논리 텍스트 노드로 해석되며, 노드가 비어 있는 경우에는 XPath 컨텍스트로 사용할 수 없습니다. |
| resolver | IXPathNSResolver | `resolver`는 XPath 식 내의 모든 접두사(예: `xml` 패키지 접두사)를 적절한 패키지 URI로 변환하도록 허용합니다. 이를 `null`로 지정하면 식 내의 모든 패키지 접두사가 [`DOMException`](../../../com.aspose.html.dom/domexception/)을 발생시키며, 코드가 `NAMESPACE_ERR`가 됩니다. |
| type | XPathResultType | 특정 `type`이 지정되면 결과가 해당 유형으로 반환됩니다. XPath 1.0 결과의 경우, 이는 [`XPathResultType`](../../xpathresulttype/) 열거형의 값 중 하나여야 합니다. |
| result | Object | `result`는 이 메서드가 재사용하고 반환할 수 있는 특정 결과 객체를 지정합니다. `null`로 지정하거나 구현이 지정된 결과를 재사용하지 않으면 새 결과 객체가 생성되어 반환됩니다. XPath 1.0 결과의 경우, 이 객체는 [`IXPathResult`](../../ixpathresult/) 유형입니다. |

### 반환 값

XPath 식 평가의 결과입니다. XPath 1.0 결과의 경우, 이 객체는 [`IXPathResult`](../../ixpathresult/) 유형입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: [`IXPathEvaluator`](../) 규칙에 따라 식이 유효하지 않을 경우 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: 결과를 지정된 유형으로 변환할 수 없을 때 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: 지정된 [`IXPathNSResolver`](../../ixpathnsresolver/)로 해석할 수 없는 패키지 접두사가 식에 포함된 경우 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: 노드가 이 [`IXPathEvaluator`](../)에서 지원되지 않는 문서에 속합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 노드가 XPath 컨텍스트 노드로 허용되는 유형이 아니거나, 요청 유형이 이 [`IXPathEvaluator`](../)에서 허용되지 않습니다. |

### 또 보기

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
