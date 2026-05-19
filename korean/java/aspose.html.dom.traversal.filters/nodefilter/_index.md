---
title: "NodeFilter 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.traversal.filters.NodeFilter 클래스. 필터는 노드를 필터링하는 방법을 아는 객체입니다"
type: docs

url: /ko/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

필터는 노드를 "filter out" 하는 방법을 알고 있는 객체입니다.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | TreeWalker 또는 NodeIterator의 논리적 뷰에서 지정된 노드가 보이는지 테스트합니다. 이 함수는 TreeWalker와 NodeIterator 구현에 의해 호출되며, 일반적으로 사용자 코드에서 직접 호출되지 않습니다. (동일한 필터를 사용해 자체 애플리케이션 로직을 안내하고 싶다면 직접 호출할 수도 있습니다.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | 이 메서드는 ECMAScript 객체 유형을 가져오는 데 사용됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | 노드를 허용합니다. NodeIterator 또는 TreeWalker에 정의된 탐색 메서드는 이 노드를 반환합니다. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | 노드를 거부합니다. NodeIterator 또는 TreeWalker에 정의된 탐색 메서드는 이 노드를 반환하지 않습니다. TreeWalker의 경우, 이 노드의 자식도 거부됩니다. NodeIterators는 이를 FILTER_SKIP의 동의어로 처리합니다. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | 이 단일 노드를 건너뜁니다. NodeIterator 또는 TreeWalker에 정의된 탐색 메서드는 이 노드를 반환하지 않습니다. NodeIterator와 TreeWalker 모두에서 이 노드의 자식은 여전히 ​​고려됩니다. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | 모든 노드를 표시합니다. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Attr 노드를 표시합니다. 이는 속성 노드를 루트로 하는 iterator 또는 tree-walker를 만들 때만 의미가 있습니다; 이 경우 속성 노드가 반복 또는 순회의 첫 번째 위치에 나타납니다. 속성은 다른 노드의 자식이 아니므로 문서 트리를 순회할 때 나타나지 않습니다. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection 노드를 표시합니다. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Comment 노드를 표시합니다. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Document 노드를 표시합니다. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment 노드를 표시합니다. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType 노드를 표시합니다. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Element 노드를 표시합니다. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Entity 노드를 표시합니다. 이는 Entity 노드를 루트로 하는 iterator 또는 tree-walker를 만들 때만 의미가 있습니다; 이 경우 Entity 노드가 순회의 첫 번째 위치에 나타납니다. 엔터티는 문서 트리의 일부가 아니므로 문서 트리를 순회할 때 나타나지 않습니다. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference 노드를 표시합니다. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Notation 노드를 표시합니다. 이는 Notation 노드를 루트로 하는 iterator 또는 tree-walker를 생성할 때만 의미가 있으며; 이 경우 Notation 노드가 순회의 첫 번째 위치에 나타납니다. Notation은 문서 트리의 일부가 아니므로 문서 트리를 순회할 때 나타나지 않습니다. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | ProcessingInstruction 노드를 표시합니다. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Text 노드를 표시합니다. |

### 또 보기

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
