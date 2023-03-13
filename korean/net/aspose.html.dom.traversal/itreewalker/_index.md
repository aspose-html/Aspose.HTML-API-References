---
title: Interface ITreeWalker
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Traversal.ITreeWalker 상호 작용. TreeWalker 객체는 whatToShow 플래그 및 필터있는 경우로 정의된 문서 보기를 사용하여 문서 트리 또는 하위 트리를 탐색하는 데 사용됩니다. 가 TreeWalker를 사용하여 탐색을 수행하는 모든 기능은 자동으로 TreeWalker가 정의한 모든 보기를 지원합니다.
type: docs
weight: 2520
url: /ko/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker 객체는 whatToShow 플래그 및 필터(있는 경우)로 정의된 문서 보기를 사용하여 문서 트리 또는 하위 트리를 탐색하는 데 사용됩니다. 가 TreeWalker를 사용하여 탐색을 수행하는 모든 기능은 자동으로 TreeWalker가 정의한 모든 보기를 지원합니다.

하위 트리의 논리적 보기에서 노드를 생략하면 완전하고 필터링되지 않은 문서의 동일한 하위 트리와 실질적으로 다른 구조가 생성될 수 있습니다. TreeWalker 보기에서 형제인 노드는 원래 보기에서 넓게 분리된 다른 노드의 자식일 수 있습니다. 예를 들어 텍스트 노드와 문서의 루트 노드인 를 제외한 모든 노드를 건너뛰는 NodeFilter를 고려하십시오. 그 결과 논리적 보기에서 모든 텍스트 노드는 형제가 되며 루트 노드의 직계 자식으로 표시되며 는 원본 문서의 구조가 얼마나 깊이 중첩되어 있는지에 관계없이 나타납니다.

또한 참조[문서 객체 모델(DOM) 레벨 2 순회 및 범위 사양](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 레벨 2

```csharp
public interface ITreeWalker : ITraversal
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | TreeWalker가 현재 위치한 노드. DOM 트리에 대한 변경으로 인해 현재 노드가 더 이상 TreeWalker의 관련 필터에 의해 허용되지 않을 수 있습니다. currentNode는 명시적으로 어떤 노드로도 설정할 수 있습니다. the 루트 노드에 의해 지정된 하위 트리 내에서 또는 필터 and whatToShow 플래그에 의해 수락됩니다. 요청된 방향으로 필터를 적용하여 현재 보기의 일부가 아니더라도 currentNode에 대한 추가 순회가 발생합니다. traversal 가 가능하지 않으면 currentNode는 변경되지 않습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | TreeWalker를 the 현재 노드의 첫 번째 보이는 자식으로 이동하고 새 노드를 반환합니다. 현재 노드에 no 보이는 자식이 있으면 null을 반환하고 current node. 를 유지합니다. |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | TreeWalker를 the 현재 노드의 마지막으로 보이는 자식으로 이동하고 새 노드를 반환합니다. 현재 노드에 no 보이는 자식이 있으면 null을 반환하고 current node. 를 유지합니다. |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | 현재 노드를 기준으로 document 순서로 TreeWalker를 다음 가시 노드로 이동하고 새 노드를 반환합니다. 만약 the 현재 노드가 다음 노드가 없거나, nextNode에 대한 검색이 TreeWalker의 root 노드에서 위로 단계적으로 를 시도하면 null을 반환하고 현재 노드를 유지합니다. |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | TreeWalker를 current 노드의 다음 형제로 이동하고 새 노드를 반환합니다. 현재 노드에 visible 다음 형제가 없으면 null을 반환하고 현재 노드를 유지합니다. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | current 노드의 가장 가까운 표시 조상 노드로 이동하여 반환합니다. parentNode에 대한 검색이 TreeWalker의 루트 노드에서 위쪽으로 step 를 시도하거나, 보이는 조상 노드를 찾는 데 실패하면 이 메서드는 현재 위치를 유지하고 null을 반환합니다. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | TreeWalker를 현재 노드를 기준으로 문서 순서로 이전에 보이는 노드로 이동하고 new 노드를 반환합니다. 현재 노드에 이전 노드가 없거나 for previousNode 검색이 the TreeWalker의 루트 노드에서 위로 올라가려고 하면 null을 반환하고 현재 노드를 유지합니다. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | TreeWalker를 the 현재 노드의 이전 형제로 이동하고 새 노드를 반환합니다. 현재 노드에 no 이전 형제가 표시되지 않으면 null을 반환하고 the 현재 노드를 유지합니다. |

### 또한보십시오

* interface [ITraversal](../itraversal/)
* 네임스페이스 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 집회 [Aspose.HTML](../../)


