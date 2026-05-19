---
title: "Node.Normalize"
second_title: "Aspose.HTML for Java API 참조"
description: "Node 메서드. 이 Node 아래의 하위 트리 전체 깊이에 있는 모든 `Text` 노드와 속성 노드를 정상 형태로 변환합니다. 이 형태에서는 요소, 주석, 처리 명령, CDATA 섹션 및 엔터티 참조와 같은 구조만이 `Text` 노드를 구분하며, 인접한 `Text` 노드나 빈 `Text` 노드가 존재하지 않게 됩니다. 이는 문서의 DOM 뷰가 저장 후 다시 로드한 것과 동일하도록 보장하는 데 사용할 수 있으며, 특정 문서 트리 구조에 의존하는 XPointer 조회와 같은 작업에 유용합니다. `Node.ownerDocument`에 연결된 `DOMConfiguration` 객체의 매개변수 `normalize-characters`가 true인 경우, 이 메서드는 `Text` 노드의 문자도 완전히 정규화합니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

[`Text`](../../text/) 노드들을 이 Node 아래의 하위 트리 전체 깊이와 속성 노드까지 포함하여 "정상" 형태로 변환합니다. 이 형태에서는 구조(예: [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), [`entity references`](../../entityreference/))만이 [`Text`](../../text/) 노드를 구분하며, 인접한 텍스트 노드나 빈 텍스트 노드가 존재하지 않습니다. 이는 문서의 DOM 뷰가 저장 후 다시 로드한 것과 동일하도록 보장하는 데 사용할 수 있으며, 특정 문서 트리 구조에 의존하는 XPointer [XPointer] 조회와 같은 작업에 유용합니다. [`Node.ownerDocument`](../ownerdocument/)에 연결된 [`DOMConfiguration`](../../../com.aspose.html/configuration/) 객체의 매개변수 "normalize-characters"가 true인 경우, 이 메서드는 텍스트 노드의 문자도 완전히 정규화합니다.

```java
public void Normalize()
```

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
