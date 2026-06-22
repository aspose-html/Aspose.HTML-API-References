---
title: "Node.CloneNode"
second_title: "Java용 Aspose.HTML API 참조"
description: "Node 메서드. Node 인터페이스의 cloneNode 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리도 복제할지 여부를 제어합니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Node 인터페이스의 cloneNode() 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리를 복제할지 여부를 제어합니다.

노드를 복제하면 모든 속성과 그 값이 복사되며, 고유(인라인) 리스너도 포함됩니다. [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/)를 사용해 추가된 이벤트 리스너나 요소 속성에 할당된 리스너(예: node.onclick = someFunction)는 복사되지 않습니다. 또한, [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) 요소의 경우, 그려진 이미지가 복사되지 않습니다.

```java
public Node CloneNode()
```

### 반환 값

새로 복제된 [`Node`](../)입니다. 복제된 노드는 부모가 없으며 문서의 일부가 아니며, [`Node.appendChild()`](../appendchild/)와 같은 메서드를 사용하여 문서의 일부인 다른 노드에 추가될 때까지 그렇습니다.

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

Node 인터페이스의 cloneNode() 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리를 복제할지 여부를 제어합니다.

노드를 복제하면 모든 속성과 그 값이 복사되며, 고유(인라인) 리스너도 포함됩니다. [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener))를 사용해 추가된 이벤트 리스너나 요소 속성에 할당된 리스너(예: node.onclick = someFunction)는 복사되지 않습니다. 또한, [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) 요소의 경우, 그려진 이미지가 복사되지 않습니다.

```java
public Node CloneNode(bool deep)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| deep | Boolean | true인 경우, 노드와 그 전체 하위 트리, 자식 [`Text`](../../text/) 노드에 있을 수 있는 텍스트까지도 복사됩니다. |

### 반환 값

새로 복제된 [Node](T:com.aspose.html.dom.Node)입니다. 복제된 노드는 부모가 없으며 문서의 일부가 아니며, [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node))와 같은 메서드를 사용하여 문서의 일부인 다른 노드에 추가될 때까지 그렇습니다.

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
