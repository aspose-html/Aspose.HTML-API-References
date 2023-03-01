---
title: Document.Evaluate
second_title: .NET API 참조용 Aspose.HTML
description: Document 방법. XPath 식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다.
type: docs
weight: 950
url: /ko/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

XPath 식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| expression | String | 구문 분석하고 평가할 XPath 표현식 문자열입니다. |
| contextNode | Node | 컨텍스트는 이 XPath 표현식의 평가를 위한 컨텍스트 노드입니다. |
| resolver | IXPathNSResolver | 해결 프로그램은 XPath 식 내에서 xml 네임스페이스 접두사를 포함하여 모든 접두사를 적절한 네임스페이스 URI로 변환하도록 허용합니다. |
| type | XPathResultType | 특정 유형을 지정하면 해당 유형으로 결과가 반환됩니다. |
| result | Object | 결과는 이 메서드에서 재사용하고 반환할 수 있는 특정 결과 개체를 지정합니다. |

### 반환 값

XPath 식의 평가 결과입니다.

### 또한보십시오

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)


