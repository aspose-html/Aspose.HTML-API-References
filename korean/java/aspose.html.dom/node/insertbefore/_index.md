---
title: "Node.InsertBefore"
second_title: "Java용 Aspose.HTML API 참조"
description: "Node 메서드. Node 인터페이스의 insertBefore 메서드는 지정된 부모 노드의 자식으로서 참조 노드 앞에 노드를 삽입합니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

Node 인터페이스의 insertBefore() 메서드는 지정된 부모 노드의 자식으로서 기준 노드 앞에 노드를 삽입합니다.

주어진 노드가 이미 문서에 존재한다면, insertBefore()는 현재 위치에서 새로운 위치로 이동시킵니다. (즉, 지정된 새로운 부모에 추가하기 전에 기존 부모로부터 자동으로 제거됩니다.)

이는 노드가 문서 내에서 동시에 두 위치에 존재할 수 없음을 의미합니다.

```java
public Node InsertBefore(Node node, Node child)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 노드 | Node | 삽입될 노드. |
| 자식 | Node | newNode가 삽입되는 이전 노드. 이것이 null이면 newNode는 해당 노드의 자식 노드 끝에 삽입됩니다. |

### 반환 값

추가된 자식을 반환합니다 (newNode가 [`DocumentFragment`](../../documentfragment/)인 경우를 제외하고, 이 경우 빈 [`DocumentFragment`](../../documentfragment/)이 반환됩니다).

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
