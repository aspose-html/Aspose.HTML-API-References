---
title: "Document.Evaluate"
second_title: "Java용 Aspose.HTML API 참조"
description: "Document 메서드. XPath 표현식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

XPath 표현식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 식 | String | 파싱 및 평가될 XPath 식 문자열입니다. |
| contextNode | Node | 컨텍스트는 이 XPath 표현식 평가를 위한 컨텍스트 노드입니다. |
| resolver | IXPathNSResolver | 해결자는 XPath 표현식 내의 모든 접두사(예: xml 패키지 접두사)를 적절한 패키지 URI로 변환할 수 있도록 허용합니다. |
| type | XPathResultType | 특정 유형이 지정된 경우, 결과는 해당 유형으로 반환됩니다. |
| result | 객체 | 결과는 이 메서드가 재사용하고 반환할 수 있는 특정 결과 객체를 지정합니다. |

### 반환 값

XPath 표현식 평가의 결과입니다.

### 또 보기

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
