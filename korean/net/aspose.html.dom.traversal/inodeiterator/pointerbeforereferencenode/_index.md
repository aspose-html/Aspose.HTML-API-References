---
title: INodeIterator.PointerBeforeReferenceNode
second_title: .NET API 참조용 Aspose.HTML
description: INodeIterator 재산. 이 플래그의 값은 entity 참조 노드의 자식이 반복자에 표시되는지 여부를 결정합니다. 거짓이면 그들과 그들의 자손이 거부될 것입니다. 이 거부는 whatToShow 및 필터보다 우선적으로 적용됩니다. 또한 이것이 현재 유일하게 NodeIterators가 개별 노드를 건너뛰는 것보다 전체 하위 트리를 거부할 수 있다는 점에 유의하십시오. 엔티티 참조가 확장되고 엔티티 참조 노드 자체를 노출하지 않는 문서의 보기를 생성하려면 whatToShow 플래그를 사용하여 엔티티 참조 node 를 숨기고 the iterator를 생성할 때 expandEntityReferences를 true로 설정합니다. 엔터티 reference 노드가 있지만 엔터티 확장이 없는 문서 보기를 생성하려면 whatToShow flags 를 사용하여 엔터티 참조 노드를 표시하고 set expandEntityReferences를 false로 설정합니다.
type: docs
weight: 10
url: /ko/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

이 플래그의 값은 entity 참조 노드의 자식이 반복자에 표시되는지 여부를 결정합니다. 거짓이면 그들과 그들의 자손이 거부될 것입니다. 이 거부는 whatToShow 및 필터보다 우선적으로 적용됩니다. 또한 이것이 현재 유일하게 NodeIterators가 개별 노드를 건너뛰는 것보다 전체 하위 트리를 거부할 수 있다는 점에 유의하십시오. 엔티티 참조가 확장되고 엔티티 참조 노드 자체를 노출하지 않는 문서의 보기를 생성하려면 whatToShow 플래그를 사용하여 엔티티 참조 node 를 숨기고 the iterator를 생성할 때 expandEntityReferences를 true로 설정합니다. 엔터티 reference 노드가 있지만 엔터티 확장이 없는 문서 보기를 생성하려면 whatToShow flags 를 사용하여 엔터티 참조 노드를 표시하고 set expandEntityReferences를 false로 설정합니다.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### 자산 가치

`진실`if [엔터티 참조 확장]; 그렇지 않으면,`거짓` .

### 또한보십시오

* interface [INodeIterator](../)
* 네임스페이스 [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* 집회 [Aspose.HTML](../../../)


