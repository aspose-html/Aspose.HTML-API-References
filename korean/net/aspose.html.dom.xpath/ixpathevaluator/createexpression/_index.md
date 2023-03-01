---
title: IXPathEvaluator.CreateExpression
second_title: .NET API 참조용 Aspose.HTML
description: IXPathEvaluator 방법. 확인된 네임스페이스를 사용하여 구문 분석된 XPath 식을 만듭니다. 이는 표현식 문자열을 보다 효율적인 내부 형식으로 컴파일하고 표현식 내에서 발생하는 모든 네임스페이스 접두사를 미리 해결할 수 있기 때문에 표현식이 응용 프로그램에서 재사용될 때 유용합니다.
type: docs
weight: 10
url: /ko/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

확인된 네임스페이스를 사용하여 구문 분석된 XPath 식을 만듭니다. 이는 표현식 문자열을 보다 효율적인 내부 형식으로 컴파일하고 표현식 내에서 발생하는 모든 네임스페이스 접두사를 미리 해결할 수 있기 때문에 표현식이 응용 프로그램에서 재사용될 때 유용합니다.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| expression | String | 구문 분석할 XPath 식 문자열입니다. |
| resolver | IXPathNSResolver | 그만큼`리졸버` 다음을 포함하여 모든 접두사 의 변환을 허용합니다.`XML` 적절한 네임스페이스 URI로의 XPath 표현식 내 네임스페이스 접두사. 이렇게 지정하면`없는` , 식 내의 모든 네임스페이스 접두사는[`DOMException`](../../../aspose.html.dom/domexception/) 코드와 함께 발생`네임스페이스_ERR`. |

### 반환 값

XPath 식의 컴파일된 형식입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: 식이 규칙에 따라 적법하지 않은 경우 발생합니다.[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: 식에 지정된 방식으로 확인할 수 없는 네임스페이스 접두사가 포함된 경우 발생합니다.[`IXPathNSResolver`](../../ixpathnsresolver/). |

### 또한보십시오

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* 네임스페이스 [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* 집회 [Aspose.HTML](../../../)


