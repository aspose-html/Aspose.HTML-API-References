---
title: Aspose.Html.Dom.Traversal
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Traversal네임스페이스에는 요소 사이를 탐색하기 위해 반복자와 트리 워커를 생성하고 문서 순서대로 노드와 그 자식을 트래버스하는 메서드가 포함되어 있습니다.
type: docs
weight: 170
url: /ko/net/aspose.html.dom.traversal/
---
**Aspose.Html.Dom.Traversal**네임스페이스에는 요소 사이를 탐색하기 위해 반복자와 트리 워커를 생성하고 문서 순서대로 노드와 그 자식을 트래버스하는 메서드가 포함되어 있습니다.

## 인터페이스

| 상호 작용 | 설명 |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal에는 문서 순서(깊이 먼저, 선주문 순회, 이는 시작 태그가 문서). 순회 기능을 지원하는 DOM 에서 DocumentTraversal은 문서 인터페이스를 구현하는 동일한 개체에 의해 구현됩니다. |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal 인터페이스는 작성자가 문서의 요소 사이를 쉽게 탐색할 수 있도록 하는 읽기 전용 속성 집합입니다. Element Traversal의 준수 구현에서 Element를 구현하는 모든 객체는 ElementTraversal 인터페이스도 구현해야 합니다. |
| [INodeFilter](./inodefilter/) | 필터는 노드를 "필터링"하는 방법을 알고 있는 개체입니다. NodeIterator 또는 TreeWalker에 NodeFilter가 제공되면 다음 노드를 반환하기 전에 필터를 적용합니다. 필터가 노드를 수락하라고 하면 순회 논리는 노드를 반환합니다. 그렇지 않으면 통과는 다음 노드를 찾고 거부된 노드가 없는 것처럼 가장합니다. |
| [INodeIterator](./inodeiterator/) | 반복자는 NodeList의 노드 집합, 특정 노드에 의해 관리되는 문서 하위 트리, 쿼리 결과 또는 노드의 다른 집합 와 같은 노드 집합을 단계별로 실행하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator의 구현에 의해 결정됩니다. DOM 레벨 2는 문서 하위 트리의 문서 순서 순회를 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal .createNodeIterator(). 를 호출하여 에 생성됩니다. |
| [ITraversal](./itraversal/) | 반복자는 NodeList의 노드 집합, 특정 노드에 의해 관리되는 문서 하위 트리, 쿼리 결과 또는 노드의 다른 집합 와 같은 노드 집합을 단계별로 실행하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator의 구현에 의해 결정됩니다. DOM 레벨 2는 문서 하위 트리의 문서 순서 순회를 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal .createNodeIterator(). 를 호출하여 에 생성됩니다. |
| [ITreeWalker](./itreewalker/) | TreeWalker 객체는 whatToShow 플래그 및 필터(있는 경우)로 정의된 문서 보기를 사용하여 문서 트리 또는 하위 트리를 탐색하는 데 사용됩니다. 가 TreeWalker를 사용하여 탐색을 수행하는 모든 기능은 자동으로 TreeWalker가 정의한 모든 보기를 지원합니다. |


