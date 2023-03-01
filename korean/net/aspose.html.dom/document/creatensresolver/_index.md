---
title: Document.CreateNSResolver
second_title: .NET API 참조용 Aspose.HTML
description: Document 방법. XPath 표현식이 문서 내에 나타난 노드의 컨텍스트에 상대적으로 쉽게 평가될 수 있도록 네임스페이스를 해결하기 위해 DOM 노드를 조정합니다. 이 어댑터는 DOM 레벨 3 방법과 같이 작동 합니다.lookupNamespaceURI time lookupNamespaceURI가 호출될 때 노드의 계층에서 사용 가능한 현재 정보를 사용하여 지정된 접두사에서 namespaceURI 를 확인하는 노드에서 암시적 xml 접두사. 도 올바르게 확인합니다.
type: docs
weight: 910
url: /ko/net/aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

XPath 표현식이 문서 내에 나타난 노드의 컨텍스트에 상대적으로 쉽게 평가될 수 있도록 네임스페이스를 해결하기 위해 DOM 노드를 조정합니다. 이 어댑터는 DOM 레벨 3 방법과 같이 작동 합니다.`lookupNamespaceURI` time lookupNamespaceURI가 호출될 때 노드의 계층에서 사용 가능한 현재 정보를 사용하여 지정된 접두사에서 namespaceURI 를 확인하는 노드에서 암시적 xml 접두사. 도 올바르게 확인합니다.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| nodeResolver | Node | 네임스페이스 확인을 위한 컨텍스트로 사용할 노드입니다. |

### 반환 값

[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/) 지정된 노드에 대한 범위의 정의와 관련하여 네임스페이스를 확인합니다.

### 또한보십시오

* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)


