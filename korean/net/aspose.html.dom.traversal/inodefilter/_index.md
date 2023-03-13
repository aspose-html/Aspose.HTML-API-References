---
title: Interface INodeFilter
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Traversal.INodeFilter 상호 작용. 필터는 노드를 필터링하는 방법을 알고 있는 개체입니다. NodeIterator 또는 TreeWalker에 NodeFilter가 제공되면 다음 노드를 반환하기 전에 필터를 적용합니다. 필터가 노드를 수락하라고 하면 순회 논리는 노드를 반환합니다. 그렇지 않으면 통과는 다음 노드를 찾고 거부된 노드가 없는 것처럼 가장합니다.
type: docs
weight: 2490
url: /ko/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

필터는 노드를 "필터링"하는 방법을 알고 있는 개체입니다. NodeIterator 또는 TreeWalker에 NodeFilter가 제공되면 다음 노드를 반환하기 전에 필터를 적용합니다. 필터가 노드를 수락하라고 하면 순회 논리는 노드를 반환합니다. 그렇지 않으면 통과는 다음 노드를 찾고 거부된 노드가 없는 것처럼 가장합니다.

DOM은 필터를 제공하지 않습니다. NodeFilter는 사용자가 자신의 필터를 제공하기 위해 구현할 수 있는 인터페이스일 뿐입니다.

NodeFilter는 노드 에서 노드로 순회하는 방법을 알 필요가 없으며 가 순회하는 데이터 구조에 대해 알 필요도 없습니다. 수행 방법만 알면 단일 노드를 평가하기 때문에 필터 작성이 매우 쉬워집니다. 하나의 필터는 여러 종류의 통과와 함께 사용할 수 있으며 코드 재사용을 권장합니다.

또한 참조[문서 객체 모델(DOM) 레벨 2 순회 및 범위 사양](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 레벨 2

```csharp
public interface INodeFilter
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | 지정된 노드가 TreeWalker 또는 NodeIterator의 논리적 보기에 표시되는지 여부를 테스트합니다. 이 함수 는 TreeWalker 및 NodeIterator의 구현에 의해 호출됩니다. 일반적으로 사용자 코드에서 직접 호출되지 않습니다. (동일한 필터를 사용하여 자신의 응용 프로그램 논리를 안내하려는 경우 그렇게 할 수 있습니다.) |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 집회 [Aspose.HTML](../../)


