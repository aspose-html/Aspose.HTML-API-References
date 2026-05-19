---
title: "com.aspose.html.dom.traversal"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.traversal 패키지는 요소 사이를 탐색하고 문서 순서대로 노드와 그 자식을 순회하기 위한 반복자와 트리 워커를 생성하는 메서드를 포함합니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/
---
The **com.aspose.html.dom.traversal** 패키지는 요소 사이를 탐색하고 문서 순서대로 노드와 그 자식을 순회하기 위한 이터레이터와 트리 워커를 생성하는 메서드를 포함합니다.

## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal은 문서 순서(깊이 우선, 전위 순회, 이는 문서의 텍스트 표현에서 시작 태그가 나타나는 순서와 동일함)대로 노드와 그 자식을 순회하기 위한 반복자와 트리 워커를 생성하는 메서드를 포함합니다. Traversal 기능을 지원하는 DOM에서는 DocumentTraversal이 Document 인터페이스를 구현하는 동일한 객체에 의해 구현됩니다. |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal 인터페이스는 문서 내 요소 사이를 쉽게 탐색할 수 있도록 하는 읽기 전용 속성 집합입니다. Element Traversal을 준수하는 구현에서는 Element를 구현하는 모든 객체가 ElementTraversal 인터페이스도 구현해야 합니다. |
| [INodeFilter](./inodefilter/) | Filters는 노드를 \"필터링\"하는 방법을 알고 있는 객체입니다. NodeIterator나 TreeWalker에 NodeFilter가 제공되면, 다음 노드를 반환하기 전에 필터를 적용합니다. 필터가 노드를 허용한다고 하면 순회 로직이 해당 노드를 반환하고, 그렇지 않으면 순회는 다음 노드를 찾아 거부된 노드가 없었던 것처럼 처리합니다. |
| [INodeIterator](./inodeiterator/) | Iterators는 노드 집합을 순차적으로 탐색하는 데 사용됩니다(예: NodeList의 노드 집합, 특정 Node가 관리하는 문서 서브트리, 쿼리 결과 또는 기타 노드 집합). 반복할 노드 집합은 NodeIterator 구현에 의해 결정됩니다. DOM Level 2는 문서 순서대로 서브트리를 순회하기 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복기의 인스턴스는 DocumentTraversal.createNodeIterator()를 호출하여 생성됩니다. |
| [ITraversal](./itraversal/) | Iterators는 노드 집합을 순차적으로 탐색하는 데 사용됩니다(예: NodeList의 노드 집합, 특정 Node가 관리하는 문서 서브트리, 쿼리 결과 또는 기타 노드 집합). 반복할 노드 집합은 NodeIterator 구현에 의해 결정됩니다. DOM Level 2는 문서 순서대로 서브트리를 순회하기 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복기의 인스턴스는 DocumentTraversal.createNodeIterator()를 호출하여 생성됩니다. |
| [ITreeWalker](./itreewalker/) | TreeWalker 객체는 whatToShow 플래그와 필터(있는 경우)로 정의된 문서 뷰를 사용하여 문서 트리 또는 서브트리를 탐색하는 데 사용됩니다. TreeWalker를 사용해 탐색을 수행하는 모든 함수는 TreeWalker가 정의한 모든 뷰를 자동으로 지원합니다. |
