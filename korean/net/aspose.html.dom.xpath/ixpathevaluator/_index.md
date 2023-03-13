---
title: Interface IXPathEvaluator
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.XPath.IXPathEvaluator 상호 작용. XPath 식의 평가는 다음에 의해 제공됩니다.IXPathEvaluator .
type: docs
weight: 2560
url: /ko/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath 식의 평가는 다음에 의해 제공됩니다.`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | 확인된 네임스페이스를 사용하여 구문 분석된 XPath 식을 만듭니다. 이는 표현식 문자열을 보다 효율적인 내부 형식으로 컴파일하고 표현식 내에서 발생하는 모든 네임스페이스 접두사를 미리 해결할 수 있기 때문에 표현식이 응용 프로그램에서 재사용될 때 유용합니다. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | XPath 표현식이 문서 내에 나타난 노드의 컨텍스트에 상대적으로 쉽게 평가될 수 있도록 네임스페이스를 해결하기 위해 DOM 노드를 조정합니다. 이 어댑터는 DOM 레벨 3 방법과 같이 작동 합니다.`lookupNamespaceURI` time lookupNamespaceURI가 호출될 때 노드의 계층에서 사용 가능한 현재 정보를 사용하여 지정된 접두사에서 namespaceURI 를 확인하는 노드에서 암시적 xml 접두사. 도 올바르게 확인합니다. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | XPath 식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* 집회 [Aspose.HTML](../../)


