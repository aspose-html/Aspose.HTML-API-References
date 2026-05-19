---
title: "ITreeWalker 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.traversal.ITreeWalker 인터페이스. TreeWalker 객체는 whatToShow 플래그와(있는 경우) 필터에 의해 정의된 문서 뷰를 사용하여 문서 트리 또는 서브트리를 탐색하는 데 사용됩니다. TreeWalker를 사용해 탐색을 수행하는 모든 함수는 TreeWalker가 정의한 뷰를 자동으로 지원합니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker 객체는 whatToShow 플래그와 필터(있는 경우)로 정의된 문서 뷰를 사용하여 문서 트리 또는 서브트리를 탐색하는 데 사용됩니다. TreeWalker를 사용해 탐색을 수행하는 모든 함수는 TreeWalker가 정의한 모든 뷰를 자동으로 지원합니다.

서브트리의 논리적 뷰에서 노드를 생략하면 전체 필터링되지 않은 문서의 동일한 서브트리와는 크게 다른 구조가 될 수 있습니다. TreeWalker 뷰에서 형제 관계에 있는 노드들이 원본 뷰에서는 서로 다른, 멀리 떨어진 노드의 자식이 될 수 있습니다. 예를 들어, 텍스트 노드와 문서의 루트 노드만 남기고 나머지 모든 노드를 건너뛰는 NodeFilter를 고려해 보십시오. 결과적인 논리적 뷰에서는 모든 텍스트 노드가 형제 관계가 되고 루트 노드의 직접 자식으로 나타나며, 원본 문서의 구조가 얼마나 깊게 중첩되어 있든 관계없이 동일합니다.

또한 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)을 참조하십시오. @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## 속성

| 이름 | 설명 |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | TreeWalker를 현재 노드의 첫 번째 보이는 자식으로 이동하고 새 노드를 반환합니다. 현재 노드에 보이는 자식이 없으면 null을 반환하고 현재 노드를 유지합니다. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | TreeWalker를 현재 노드의 마지막 보이는 자식으로 이동하고 새 노드를 반환합니다. 현재 노드에 보이는 자식이 없으면 null을 반환하고 현재 노드를 유지합니다. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | TreeWalker를 현재 노드에 대한 문서 순서상의 다음 보이는 노드로 이동하고 새 노드를 반환합니다. 현재 노드에 다음 노드가 없거나 nextNode 검색이 TreeWalker의 루트 노드에서 위로 이동하려 할 경우 null을 반환하고 현재 노드를 유지합니다. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | TreeWalker를 현재 노드의 다음 형제로 이동하고 새 노드를 반환합니다. 현재 노드에 보이는 다음 형제가 없으면 null을 반환하고 현재 노드를 유지합니다. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | 현재 노드의 가장 가까운 보이는 조상 노드로 이동하고 반환합니다. parentNode 검색이 TreeWalker의 루트 노드에서 위로 이동하려 하거나 보이는 조상 노드를 찾지 못하면 현재 위치를 유지하고 null을 반환합니다. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | TreeWalker를 현재 노드에 상대적인 문서 순서에서 이전에 보이는 노드로 이동시키고 새 노드를 반환합니다. 현재 노드에 이전 노드가 없거나 previousNode 검색이 TreeWalker의 루트 노드에서 위로 이동하려 할 경우 null을 반환하고 현재 노드를 유지합니다. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | TreeWalker를 현재 노드의 이전 형제로 이동시키고 새 노드를 반환합니다. 현재 노드에 보이는 이전 형제가 없으면 null을 반환하고 현재 노드를 유지합니다. |

### 또 보기

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
