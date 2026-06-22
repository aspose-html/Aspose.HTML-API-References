---
title: "IXPathEvaluator 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.xpath.IXPathEvaluator 인터페이스. XPath 식의 평가는 IXPathEvaluator에 의해 제공됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath 식의 평가는 `IXPathEvaluator`에 의해 제공됩니다.

```java
public interface IXPathEvaluator
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | 해결된 패키지를 사용하여 구문 분석된 XPath 표현식을 생성합니다. 이는 표현식 문자열을 보다 효율적인 내부 형태로 컴파일하고 표현식 내에 나타나는 모든 패키지 접두사를 사전 해결할 수 있게 하므로, 애플리케이션에서 표현식을 재사용할 때 유용합니다. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | 문서 내에서 나타난 노드의 컨텍스트에 상대적으로 XPath 표현식을 쉽게 평가할 수 있도록 모든 DOM 노드를 패키지 해결에 맞게 변환합니다. 이 어댑터는 `lookupNamespaceURI` 메서드와 같이 작동하여, 호출 시 노드 계층 구조에 현재 존재하는 정보를 사용해 주어진 접두사에서 packageURI를 해결하고, 암시적 xml 접두사도 올바르게 해결합니다. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | XPath 표현식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다. |

### 또 보기

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
