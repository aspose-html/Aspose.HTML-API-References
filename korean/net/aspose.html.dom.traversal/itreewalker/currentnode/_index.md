---
title: ITreeWalker.CurrentNode
second_title: .NET API 참조용 Aspose.HTML
description: ITreeWalker 재산. TreeWalker가 현재 위치한 노드. DOM 트리에 대한 변경으로 인해 현재 노드가 더 이상 TreeWalker의 관련 필터에 의해 허용되지 않을 수 있습니다. currentNode는 명시적으로 어떤 노드로도 설정할 수 있습니다. the 루트 노드에 의해 지정된 하위 트리 내에서 또는 필터 and whatToShow 플래그에 의해 수락됩니다. 요청된 방향으로 필터를 적용하여 현재 보기의 일부가 아니더라도 currentNode에 대한 추가 순회가 발생합니다. traversal 가 가능하지 않으면 currentNode는 변경되지 않습니다.
type: docs
weight: 10
url: /ko/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker가 현재 위치한 노드. DOM 트리에 대한 변경으로 인해 현재 노드가 더 이상 TreeWalker의 관련 필터에 의해 허용되지 않을 수 있습니다. currentNode는 명시적으로 어떤 노드로도 설정할 수 있습니다. the 루트 노드에 의해 지정된 하위 트리 내에서 또는 필터 and whatToShow 플래그에 의해 수락됩니다. 요청된 방향으로 필터를 적용하여 현재 보기의 일부가 아니더라도 currentNode에 대한 추가 순회가 발생합니다. traversal 가 가능하지 않으면 currentNode는 변경되지 않습니다.

```csharp
public Node CurrentNode { get; set; }
```

### 자산 가치

현재 노드.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: set currentNode를 null로 설정하려고 하면 발생합니다. |

### 또한보십시오

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* 네임스페이스 [Aspose.Html.Dom.Traversal](../../itreewalker/)
* 집회 [Aspose.HTML](../../../)


