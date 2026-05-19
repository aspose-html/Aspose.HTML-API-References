---
title: "Node.RemoveChild"
second_title: "Aspose.HTML for Java API 참조"
description: "Node 메서드. Node 인터페이스의 removeChild 메서드는 DOM에서 자식 노드를 제거하고 제거된 노드를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Node 인터페이스의 removeChild() 메서드는 DOM에서 자식 노드를 제거하고 제거된 노드를 반환합니다.

참고: 제거된 자식에 대한 참조가 유지되는 한, 해당 객체는 메모리에 남아 있지만 DOM의 일부는 아닙니다. 이후 코드에서 다시 사용할 수 있습니다. removeChild()의 반환값을 저장하지 않고 다른 참조도 유지되지 않으면, 짧은 시간 후에 메모리에서 자동으로 삭제됩니다.

```java
public Node RemoveChild(Node child)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| child | Node | DOM에서 제거될 자식 노드인 [`Node`](../)입니다. |

### 반환 값

[`Node.cloneNode()`](../clonenode/)와 달리, 반환값은 연관된 [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) 객체를 보존합니다.

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
