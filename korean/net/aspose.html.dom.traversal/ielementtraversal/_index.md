---
title: Interface IElementTraversal
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Traversal.IElementTraversal 상호 작용. ElementTraversal 인터페이스는 작성자가 문서의 요소 사이를 쉽게 탐색할 수 있도록 하는 읽기 전용 속성 집합입니다. Element Traversal의 준수 구현에서 Element를 구현하는 모든 객체는 ElementTraversal 인터페이스도 구현해야 합니다.
type: docs
weight: 2480
url: /ko/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal 인터페이스는 작성자가 문서의 요소 사이를 쉽게 탐색할 수 있도록 하는 읽기 전용 속성 집합입니다. Element Traversal의 준수 구현에서 Element를 구현하는 모든 객체는 ElementTraversal 인터페이스도 구현해야 합니다.

```csharp
public interface IElementTraversal
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | 이 요소의 자식인 요소 노드의 현재 수를 반환합니다. 이 요소에 nodeType이 1. 인 하위 노드가 없는 경우 0입니다. |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | 이 요소의 첫 번째 자식 요소 노드를 반환합니다. 이 요소에 자식 요소가 없으면 null입니다. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | 이 요소의 마지막 자식 요소 노드를 반환합니다. 이 요소에 자식 요소가 없으면 null입니다. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | 이 요소의 다음 형제 요소 노드를 반환합니다. 이 요소에 문서 트리에서 이 항목 뒤에 오는 요소 형제 노드가 없는 경우 null입니다. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | 이 요소의 이전 형제 요소 노드를 반환합니다. 이 요소에 문서 트리에서 이 요소 앞에 오는 요소 형제 노드가 없는 경우 null입니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 집회 [Aspose.HTML](../../)


