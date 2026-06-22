---
title: "com.aspose.html.dom.xpath"
second_title: "Java용 Aspose.HTML API 참조"
description: "이 패키지는 XML 문서의 요소와 속성을 탐색하는 메서드를 포함합니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/
---
패키지는 XML 문서의 요소와 속성을 탐색하는 메서드를 포함합니다.

## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | XPath 표현식의 평가는 [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/)에 의해 제공됩니다. |
| [IXPathExpression](./ixpathexpression/) | `XPathExpression` 인터페이스는 구문 분석되고 해결된 XPath 표현식을 나타냅니다. |
| [IXPathNamespace](./ixpathpackage/) | XPathNamespace 인터페이스는 DOM에 없는 XPath 패키지 노드 유형을 나타내기 위해 XPathResult 인터페이스에 의해 반환됩니다. |
| [IXPathNSResolver](./ixpathnsresolver/) | `XPathNSResolver` 인터페이스는 표현식의 `prefix` 문자열이 `packageURI` 문자열에 올바르게 바인딩되도록 허용합니다. [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/)는 노드에서 [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) 구현을 생성할 수 있으며, 이 인터페이스는 어떤 애플리케이션에 의해 구현될 수도 있습니다. |
| [IXPathResult](./ixpathresult/) | `XPathResult` 인터페이스는 특정 노드의 컨텍스트 내에서 XPath 1.0 표현식 평가 결과를 나타냅니다. XPath 표현식의 평가는 다양한 결과 유형을 가질 수 있기 때문에, 이 객체는 결과의 유형과 값을 탐색하고 조작할 수 있게 합니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | 이 결과가 어떤 유형인지 나타내는 부호 없는 짧은 정수입니다. 특정 `type`이 지정되면, 필요한 경우 및 가능한 경우 XPath 유형 변환을 사용하여 해당 유형으로 결과가 반환됩니다. |
