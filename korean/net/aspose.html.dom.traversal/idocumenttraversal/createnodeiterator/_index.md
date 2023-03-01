---
title: IDocumentTraversal.CreateNodeIterator
second_title: .NET API 참조용 Aspose.HTML
description: IDocumentTraversal 방법. 지정한 노드 에 뿌리를 둔 하위 트리에 새 NodeIterator를 만듭니다.
type: docs
weight: 10
url: /ko/net/aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

지정한 노드 에 뿌리를 둔 하위 트리에 새 NodeIterator를 만듭니다.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| root | Node | 자식과 함께 반복될 노드입니다. 반복자는 초기에 이 노드 바로 앞에 위치합니다. 이 위치를 설정할 때 whatToShow 플래그와 필터(있는 경우)는 고려하지 않습니다. 루트는 null이 아니어야 합니다. |

### 반환 값

새로 생성된 NodeIterator.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또한보십시오

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* 네임스페이스 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 집회 [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

지정한 노드 에 뿌리를 둔 하위 트리에 새 NodeIterator를 만듭니다.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| root | Node | 자식과 함께 반복될 노드입니다. 반복자는 초기에 이 노드 바로 앞에 위치합니다. 이 위치를 설정할 때 whatToShow 플래그와 필터(있는 경우)는 고려하지 않습니다. 루트는 null이 아니어야 합니다. |
| whatToShow | Int64 | 플래그는 반복자가 표시하는 트리의 논리적 보기에 나타날 수 있는 노드 유형을 지정합니다. possible SHOW_ 값 집합에 대해서는 NodeFilter의 설명을 참조하십시오. 이러한 플래그는 OR을 사용하여 결합할 수 있습니다. |

### 반환 값

새로 생성된 NodeIterator.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또한보십시오

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* 네임스페이스 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 집회 [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

지정한 노드 에 뿌리를 둔 하위 트리에 새 NodeIterator를 만듭니다.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| root | Node | 자식과 함께 반복될 노드입니다. 반복자는 초기에 이 노드 바로 앞에 위치합니다. 이 위치를 설정할 때 whatToShow 플래그와 필터(있는 경우)는 고려하지 않습니다. 루트는 null이 아니어야 합니다. |
| whatToShow | Int64 | 플래그는 반복자가 표시하는 트리의 논리적 보기에 나타날 수 있는 노드 유형을 지정합니다. possible SHOW_ 값 집합에 대해서는 NodeFilter의 설명을 참조하십시오. 이러한 플래그는 OR을 사용하여 결합할 수 있습니다. |
| filter | INodeFilter | this TreeWalker와 함께 사용할 NodeFilter 또는 필터가 없음을 나타내는 null입니다. |

### 반환 값

새로 생성된 NodeIterator.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또한보십시오

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* 네임스페이스 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 집회 [Aspose.HTML](../../../)


