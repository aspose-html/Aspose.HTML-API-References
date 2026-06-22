---
title: "IXPathEvaluator.CreateExpression"
second_title: "Java용 Aspose.HTML API 참조"
description: "IXPathEvaluator 메서드. 해석된 패키지를 포함하는 파싱된 XPath 식을 생성합니다. 이 식을 애플리케이션에서 재사용할 경우, 식 문자열을 보다 효율적인 내부 형태로 컴파일하고 식 내에 발생하는 모든 패키지 접두사를 사전 해석할 수 있게 해 주므로 유용합니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

해결된 패키지를 사용하여 구문 분석된 XPath 표현식을 생성합니다. 이는 표현식 문자열을 보다 효율적인 내부 형태로 컴파일하고 표현식 내에 나타나는 모든 패키지 접두사를 사전 해결할 수 있게 하므로, 애플리케이션에서 표현식을 재사용할 때 유용합니다.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 식 | String | 파싱될 XPath 식 문자열입니다. |
| resolver | IXPathNSResolver | `resolver`는 XPath 식 내의 모든 접두사, 특히 `xml` 패키지 접두사를 적절한 패키지 URI로 변환하도록 허용합니다. 이것을 `null`로 지정하면 식 내의 모든 패키지 접두사가 [`DOMException`](../../../com.aspose.html.dom/domexception/)을 발생시키며, 코드가 `NAMESPACE_ERR`가 됩니다. |

### 반환 값

XPath 식의 컴파일된 형태입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: [`IXPathEvaluator`](../) 규칙에 따라 식이 유효하지 않을 경우 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: 지정된 [`IXPathNSResolver`](../../ixpathnsresolver/)로 해석할 수 없는 패키지 접두사가 식에 포함된 경우 발생합니다. |

### 또 보기

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
