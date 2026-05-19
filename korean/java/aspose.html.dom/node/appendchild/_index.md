---
title: "Node.AppendChild"
second_title: "Aspose.HTML for Java API 참조"
description: "Node 메서드. Node 인터페이스의 appendChild 메서드는 지정된 부모 노드의 자식 목록 끝에 노드를 추가합니다. 주어진 자식이 문서에 이미 존재하는 노드에 대한 참조인 경우, appendChild는 해당 노드를 현재 위치에서 새로운 위치로 이동시키며, 다른 노드에 추가하기 전에 부모 노드에서 제거할 필요가 없습니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

Node 인터페이스의 appendChild() 메서드는 지정된 부모 노드의 자식 목록 끝에 노드를 추가합니다. 주어진 자식이 문서에 이미 존재하는 노드에 대한 참조인 경우, appendChild()는 현재 위치에서 새로운 위치로 이동시킵니다(다른 노드에 추가하기 전에 노드를 부모 노드에서 제거할 필요가 없습니다).

이는 노드가 문서 내에서 동시에 두 지점에 존재할 수 없음을 의미합니다. 따라서 노드가 이미 부모를 가지고 있다면 먼저 제거된 후 새로운 위치에 추가됩니다. [`Node.cloneNode()`](../clonenode/) 메서드를 사용하면 새 부모 아래에 추가하기 전에 노드의 복사본을 만들 수 있습니다. [`cloneNode`](../clonenode/)으로 만든 복사본은 자동으로 동기화되지 않습니다.

```java
public Node AppendChild(Node node)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 노드 | Node | 주어진 부모 노드(보통 요소)에 추가할 노드. |

### 반환 값

추가된 자식(aChild)인 Node이며, aChild가 [`DocumentFragment`](../../documentfragment/)인 경우를 제외하고는 빈 [`DocumentFragment`](../../documentfragment/)이 반환됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../domexception/) | DOM 트리의 제약 조건이 위배될 때 발생합니다. |

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
