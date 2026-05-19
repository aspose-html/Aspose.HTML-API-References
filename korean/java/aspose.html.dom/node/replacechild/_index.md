---
title: "Node.ReplaceChild"
second_title: "Aspose.HTML for Java API 참조"
description: "Node 메서드. 자식 목록에서 child 노드 oldChild를 newChild로 교체하고 oldChild 노드를 반환합니다. newChild가 DocumentFragment 객체인 경우, oldChild는 동일한 순서로 삽입되는 DocumentFragment의 모든 자식으로 교체됩니다. newChild가 이미 트리에 존재한다면 먼저 제거됩니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/replacechild/
---
## Node.ReplaceChild method

자식 목록에서 child 노드 oldChild를 newChild로 교체하고 oldChild 노드를 반환합니다. newChild가 [`DocumentFragment`](../../documentfragment/) 객체인 경우, oldChild는 동일한 순서로 삽입되는 모든 [`DocumentFragment`](../../documentfragment/) 자식으로 교체됩니다. newChild가 이미 트리에 존재한다면 먼저 제거됩니다.

```java
public Node ReplaceChild(Node node, Node child)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 노드 | Node | oldChild를 교체할 새로운 노드. |
| 자식 | Node | 교체될 자식 노드. |

### 반환 값

교체된 Node. 이는 oldChild와 동일한 노드입니다.

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
