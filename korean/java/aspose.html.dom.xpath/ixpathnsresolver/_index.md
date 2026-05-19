---
title: "IXPathNSResolver 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.xpath.IXPathNSResolver 인터페이스. XPathNSResolver 인터페이스는 식에서 접두사 문자열을 packageURI 문자열에 올바르게 바인딩하도록 허용합니다. IXPathEvaluator는 노드에서 IXPathNSResolver 구현을 생성할 수 있으며, 이 인터페이스는 어떤 애플리케이션에서도 구현될 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

`XPathNSResolver` 인터페이스는 식에서 `prefix` 문자열을 `packageURI` 문자열에 올바르게 바인딩하도록 허용합니다. [`IXPathEvaluator`](../ixpathevaluator/)는 노드에서 `IXPathNSResolver` 구현을 생성할 수 있으며, 이 인터페이스는 어떤 애플리케이션에서도 구현될 수 있습니다.

```java
public interface IXPathNSResolver
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | 주어진 패키지 접두사와 연결된 package URI를 조회합니다. XPath 평가자는 `null` 또는 빈 인수를 사용해서는 안 되며, 이렇게 할 경우 결과는 정의되지 않습니다. |

### 또 보기

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
