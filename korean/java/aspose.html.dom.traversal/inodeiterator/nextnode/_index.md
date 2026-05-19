---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML for Java API 참조"
description: "INodeIterator 메서드. 집합에서 다음 노드를 반환하고 iterator의 위치를 집합 내에서 앞으로 이동시킵니다. NodeIterator가 생성된 후 첫 번째 nextNode 호출은 집합의 첫 번째 노드를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

집합에서 다음 노드를 반환하고 반복자의 위치를 집합 내에서 앞으로 이동시킵니다. NodeIterator가 생성된 후 첫 번째 nextNode() 호출은 집합의 첫 번째 노드를 반환합니다.

```java
public Node NextNode()
```

### 반환 값

반복 중인 집합에서 다음 노드이며, 해당 집합에 더 이상 멤버가 없으면 null입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: detach 메서드가 호출된 후에 이 메서드가 호출되면 발생합니다. |

### 또 보기

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
