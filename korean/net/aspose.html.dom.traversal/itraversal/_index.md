---
title: Interface ITraversal
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Traversal.ITraversal 상호 작용. 반복자는 NodeList의 노드 집합 특정 노드에 의해 관리되는 문서 하위 트리 쿼리 결과 또는 노드의 다른 집합 와 같은 노드 집합을 단계별로 실행하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator의 구현에 의해 결정됩니다. DOM 레벨 2는 문서 하위 트리의 문서 순서 순회를 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal .createNodeIterator. 를 호출하여 에 생성됩니다.
type: docs
weight: 2510
url: /ko/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

반복자는 NodeList의 노드 집합, 특정 노드에 의해 관리되는 문서 하위 트리, 쿼리 결과 또는 노드의 다른 집합 와 같은 노드 집합을 단계별로 실행하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator의 구현에 의해 결정됩니다. DOM 레벨 2는 문서 하위 트리의 문서 순서 순회를 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal .createNodeIterator(). 를 호출하여 에 생성됩니다.

또한 참조[문서 객체 모델(DOM) 레벨 2 순회 및 범위 사양](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 레벨 2

```csharp
public interface ITraversal : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | 노드를 가리는 데 사용되는 NodeFilter입니다. |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | it 가 생성될 때 지정된 NodeIterator의 루트 노드입니다. |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | 이 속성은 반복자를 통해 표시되는 노드 유형을 결정합니다. 사용 가능한 상수 세트는 NodeFilter 인터페이스에서 정의됩니다. 에 의해 승인되지 않은 노드는 whatToShow를 건너뛸 수 있지만 그 자식은 여전히 고려될 수 있습니다. 이 건너뛰기는 필터(있는 경우 )보다 우선합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 집회 [Aspose.HTML](../../)


