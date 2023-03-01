---
title: Class NodeFilter
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter 수업. 필터는 노드를 필터링하는 방법을 알고 있는 개체입니다.
type: docs
weight: 2460
url: /ko/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

필터는 노드를 "필터링"하는 방법을 알고 있는 개체입니다.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | 지정된 노드가 a TreeWalker 또는 NodeIterator의 논리적 보기에 표시되는지 여부를 테스트합니다. 이 function 는 TreeWalker 및 NodeIterator의 구현에 의해 호출됩니다. 일반적으로 from 사용자 코드에서 직접 호출되지 않습니다. (same 필터를 사용하여 자체 애플리케이션 로직을 안내하려는 경우 그렇게 할 수 있습니다.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | 노드를 수락합니다. NodeIterator 또는 TreeWalker에 대해 정의된 탐색 메서드는 이 node. 를 반환합니다. |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | 노드를 거부합니다. NodeIterator 또는 TreeWalker에 대해 정의된 탐색 메서드는 이 노드를 반환하지 않습니다. TreeWalker의 경우 이 노드 의 자식도 거부됩니다. NodeIterators는 이것을 FILTER_SKIP. 의 동의어로 취급합니다. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | 이 단일 노드를 건너뜁니다. NodeIterator 또는 TreeWalker에 대해 정의된 탐색 메서드는 이 노드를 반환하지 않습니다. NodeIterator 및 TreeWalker 모두에 대해 이 노드의 자식은 여전히 고려됩니다. |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | 모든 노드 표시. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Attr 노드를 표시합니다. 이는 속성 노드를 루트로 사용하여 반복자 또는 트리 워커를 생성할 때만 의미가 있습니다. 이 경우 속성 노드 가 반복 또는 탐색의 첫 번째 위치에 나타납니다. 속성은 다른 노드의 자식이 아니므로 문서 트리를 탐색할 때 나타나지 않습니다. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection 노드 표시. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | 주석 노드 표시. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | 문서 노드 표시. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment 노드 표시. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType 노드 표시. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | 요소 노드 표시. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | 엔터티 노드를 표시합니다. 이는 엔티티 노드를 루트로 사용하여 반복자 또는 트리 워커인 를 생성할 때만 의미가 있습니다. 이 경우 순회의 첫 번째 위치에 Entity 노드가 나타납니다. 엔터티는 문서 트리의 일부가 아니므로 가 문서 트리를 통과할 때 나타나지 않습니다. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference 노드 표시. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | 표기법 노드를 표시합니다. 이는 Notation 노드를 루트로 사용하여 반복자 또는 트리 워커를 생성할 때만 의미가 있습니다. 이 경우 Notation 노드가 탐색의 첫 번째 위치에 나타납니다. 표기법은 문서 트리의 일부가 아니므로 문서 트리를 탐색할 때 표시되지 않습니다. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | ProcessingInstruction 노드 표시. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | 텍스트 노드 표시. |

### 또한보십시오

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* 네임스페이스 [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* 집회 [Aspose.HTML](../../)


