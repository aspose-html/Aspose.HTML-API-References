---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.HTML for Java API 참조"
description: "ITreeWalker 속성. TreeWalker가 현재 위치한 노드입니다. DOM 트리의 변경으로 인해 현재 노드가 TreeWalker와 연결된 필터에 의해 더 이상 허용되지 않을 수 있습니다. currentNode는 루트 노드가 지정한 하위 트리 내에 있든 없든, 필터와 whatToShow 플래그에 의해 허용되는지 여부와 관계없이 명시적으로 어떤 노드로든 설정할 수 있습니다. 추가 탐색은 요청된 방향으로 필터를 적용하여 currentNode를 기준으로 수행되며, 탐색이 불가능한 경우 currentNode는 변경되지 않습니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker가 현재 위치한 노드입니다. DOM 트리의 변경으로 인해 현재 노드가 TreeWalker와 연결된 필터에 의해 더 이상 허용되지 않을 수 있습니다. currentNode는 루트 노드가 지정한 하위 트리 내에 있든 없든, 필터와 whatToShow 플래그에 의해 허용되는지 여부와 관계없이 명시적으로 어떤 노드로든 설정할 수 있습니다. 추가 탐색은 요청된 방향으로 필터를 적용하여 currentNode를 기준으로 수행되며, 탐색이 불가능한 경우 currentNode는 변경되지 않습니다.

```java
public Node CurrentNode { get; set; }
```

### Property Value

현재 노드.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: currentNode를 null로 설정하려는 시도가 있을 경우 발생합니다. |

### 또 보기

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
