---
title: IXPathExpression.Evaluate
second_title: .NET API 참조용 Aspose.HTML
description: IXPathExpression 방법. 이 XPath 식을 평가하고 결과를 반환합니다.
type: docs
weight: 10
url: /ko/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

이 XPath 식을 평가하고 결과를 반환합니다.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| contextNode | Node | 그만큼`문맥` 이 XPath 표현식의 평가를 위한 컨텍스트 노드입니다. 만약[`IXPathEvaluator`](../../ixpathevaluator/) 를 캐스팅하여 얻었다.[`Document`](../../../aspose.html.dom/document/) 그런 다음 이것은 동일한 문서가 소유해야 하며[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , 또는XPathNamespace 마디. 컨텍스트 노드가[`Text`](../../../aspose.html.dom/text/) 또는[`CDATASection`](../../../aspose.html.dom/cdatasection/), 그러면 노드가 비어 있지 않는 한 컨텍스트는 XPath에서 볼 수 있는 전체 논리 텍스트 노드로 해석됩니다. |
| type | XPathResultType | 특정한 경우`유형` 이 지정되면 결과는 XPath 변환에 의존하는 지정된 유형을 반환하도록 강제되고 원하는 강제 변환이 가능하지 않으면 실패합니다. 이것은 가 다음 값 중 하나여야 합니다.[`XPathResultType`](../../xpathresulttype/). |
| result | Object | 그만큼`결과` 이 메서드에 의해 재사용되고 반환될 수 있는 특정 결과 개체를 지정합니다. 이렇게 지정하면`없는`또는 구현이 지정된 결과를 재사용하지 않으면 새 결과 개체가 구성되어 반환됩니다. XPath 1.0 결과의 경우 이 개체는 유형입니다.[`IXPathResult`](../../ixpathresult/). |

### 반환 값

XPath 표현식의 평가 결과입니다. XPath 1.0 결과의 경우 이 개체는 유형입니다.[`IXPathResult`](../../ixpathresult/).

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: 지정된 유형을 반환하도록 결과를 변환할 수 없는 경우 발생합니다. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: 노드가 에서 지원하지 않는 문서에서 온 것입니다.[`IXPathEvaluator`](../../ixpathevaluator/) 이것을 만든[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 노드가 XPath 컨텍스트 노드 로 허용된 유형이 아니거나 요청 유형이 이 노드에서 허용되지 않습니다.[`IXPathExpression`](../). |

### 또한보십시오

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* 네임스페이스 [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* 집회 [Aspose.HTML](../../../)


