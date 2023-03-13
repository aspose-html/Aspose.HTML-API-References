---
title: Interface INodeIterator
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Traversal.INodeIterator 상호 작용. 반복자는 NodeList의 노드 집합 특정 노드에 의해 관리되는 문서 하위 트리 쿼리 결과 또는 노드의 다른 집합 와 같은 노드 집합을 단계별로 실행하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator의 구현에 의해 결정됩니다. DOM 레벨 2는 문서 하위 트리의 문서 순서 순회를 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal .createNodeIterator. 를 호출하여 에 생성됩니다.
type: docs
weight: 2500
url: /ko/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

반복자는 NodeList의 노드 집합, 특정 노드에 의해 관리되는 문서 하위 트리, 쿼리 결과 또는 노드의 다른 집합 와 같은 노드 집합을 단계별로 실행하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator의 구현에 의해 결정됩니다. DOM 레벨 2는 문서 하위 트리의 문서 순서 순회를 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal .createNodeIterator(). 를 호출하여 에 생성됩니다.

또한 참조[문서 객체 모델(DOM) 레벨 2 순회 및 범위 사양](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 레벨 2

```csharp
public interface INodeIterator : ITraversal
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | 이 플래그의 값은 entity 참조 노드의 자식이 반복자에 표시되는지 여부를 결정합니다. 거짓이면 그들과 그들의 자손이 거부될 것입니다. 이 거부는 whatToShow 및 필터보다 우선적으로 적용됩니다. 또한 이것이 현재 유일하게 NodeIterators가 개별 노드를 건너뛰는 것보다 전체 하위 트리를 거부할 수 있다는 점에 유의하십시오. 엔티티 참조가 확장되고 엔티티 참조 노드 자체를 노출하지 않는 문서의 보기를 생성하려면 whatToShow 플래그를 사용하여 엔티티 참조 node 를 숨기고 the iterator를 생성할 때 expandEntityReferences를 true로 설정합니다. 엔터티 reference 노드가 있지만 엔터티 확장이 없는 문서 보기를 생성하려면 whatToShow flags 를 사용하여 엔터티 참조 노드를 표시하고 set expandEntityReferences를 false로 설정합니다. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | 현재 참조 노드입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | iterated 집합에서 NodeIterator를 분리하여 계산 리소스를 해제하고 iterator 를 INVALID 상태로 둡니다. 분리가 호출된 후 nextNode 또는 previousNode에 대한 호출은 예외 INVALID_STATE_ERR. 를 발생시킵니다. |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | 집합에서 다음 노드를 반환하고 집합에서 the 반복자의 위치를 전진시킵니다. NodeIterator가 생성된 후 nextNode()에 대한 첫 번째 호출은 set. 의 첫 번째 노드를 반환합니다. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | 집합의 이전 노드를 반환하고 집합에서 the NodeIterator의 위치를 뒤로 이동합니다. |

### 또한보십시오

* interface [ITraversal](../itraversal/)
* 네임스페이스 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 집회 [Aspose.HTML](../../)


