---
title: IXPathEvaluator.Evaluate
second_title: .NET API 참조용 Aspose.HTML
description: IXPathEvaluator 방법. XPath 식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다.
type: docs
weight: 30
url: /ko/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

XPath 식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| expression | String | 구문 분석하고 평가할 XPath 표현식 문자열입니다. |
| contextNode | Node | 그만큼`문맥` 이 XPath 식의 평가를 위한 컨텍스트 노드입니다. 만약[`IXPathEvaluator`](../) 를 주조하여 얻었습니다.[`Document`](../../../aspose.html.dom/document/) 이것은 동일한 문서가 소유해야 하며 여야 합니다.[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , 또는XPathNamespace 마디. 컨텍스트 노드가[`Text`](../../../aspose.html.dom/text/) 또는 [`CDATASection`](../../../aspose.html.dom/cdatasection/)컨텍스트는 XPath 컨텍스트로 제공되지 않을 수 있는 경우 노드가 비어 있지 않는 한 XPath에서 볼 수 있는 전체 논리 텍스트 노드 로 해석됩니다. |
| resolver | IXPathNSResolver | 그만큼`리졸버` 를 포함하여 모든 접두사의 번역을 허용합니다.`XML` 적절한 네임스페이스 URI에 대한 XPath 표현식 내의 네임스페이스 접두사. 다음과 같이 지정된 경우`없는` , 식 내의 모든 네임스페이스 접두사는 가 됩니다.[`DOMException`](../../../aspose.html.dom/domexception/) 코드와 함께 던져지고`네임스페이스_ERR`. |
| type | XPathResultType | 특정한 경우`유형` 지정되면 결과는 해당 유형의 로 반환됩니다. XPath 1.0 결과의 경우 값 중 하나여야 합니다.[`XPathResultType`](../../xpathresulttype/) 열거형 |
| result | Object | 그만큼`결과` 를 재사용하고 이 메서드에서 반환할 수 있는 특정 결과 개체를 지정합니다. 이렇게 지정하면`없는`또는 구현이 지정된 결과를 재사용하지 않으면 새 결과 개체가 구성되어 반환됩니다. XPath 1.0 결과의 경우 이 개체는[`IXPathResult`](../../ixpathresult/). |

### 반환 값

XPath 표현식의 평가 결과입니다. XPath 1.0 결과의 경우 이 객체 는[`IXPathResult`](../../ixpathresult/).

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: 표현식이 의 규칙에 따라 적법하지 않은 경우 발생합니다.[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: 지정된 유형을 반환하도록 결과를 변환할 수 없는 경우 발생합니다. |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: 식에 지정된 방식으로 확인할 수 없는 네임스페이스 접두사 가 포함된 경우 발생합니다.[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: 노드는 이것에 의해 지원되지 않는 문서에서 왔습니다.[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 노드가 XPath 컨텍스트 노드로 허용된 유형이 아니거나 요청 유형이 이 항목에서 허용되지 않습니다.[`IXPathEvaluator`](../). |

### 또한보십시오

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* 네임스페이스 [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* 집회 [Aspose.HTML](../../../)


