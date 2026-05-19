---
title: "Node.LookupPrefix"
second_title: "Aspose.HTML for Java API 참조"
description: "Node 메서드. Node 인터페이스의 lookupPrefix 메서드는 주어진 패키지 URI에 대한 접두사가 존재하면 해당 접두사를 포함한 문자열을 반환하고, 없으면 null을 반환합니다. 여러 접두사가 가능한 경우 첫 번째 접두사가 반환됩니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

Node 인터페이스의 lookupPrefix() 메서드는 주어진 패키지 URI에 대한 접두사가 있으면 해당 접두사를 포함한 문자열을 반환하고, 없으면 null을 반환합니다. 여러 접두사가 가능한 경우 첫 번째 접두사가 반환됩니다.

```java
public String LookupPrefix(String packageURI)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| packageURI | String | 접두사를 찾을 패키지를 포함하는 문자열입니다. |

### 반환 값

해당 접두사를 포함한 문자열이거나, 찾지 못한 경우 null입니다. 패키지가 null이거나 빈 문자열이면 lookupPrefix()는 null을 반환합니다.

노드가 [`DocumentType`](../../documenttype/) 또는 [`DocumentFragment`](../../documentfragment/)인 경우, lookupPrefix()는 항상 null을 반환합니다.

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
