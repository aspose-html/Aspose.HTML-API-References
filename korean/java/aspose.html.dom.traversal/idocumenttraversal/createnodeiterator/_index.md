---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.HTML for Java API 참조"
description: "IDocumentTraversal 메서드. 지정된 노드를 루트로 하는 서브트리 위에 새로운 NodeIterator를 생성합니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

지정된 노드를 루트로 하는 서브트리에서 새로운 NodeIterator를 생성합니다.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 루트 | Node | 자식과 함께 반복될 노드. 이터레이터는 처음에 이 노드 바로 앞에 위치합니다. whatToShow 플래그와 필터(있는 경우)는 이 위치를 설정할 때 고려되지 않습니다. 루트는 null이면 안 됩니다. |

### 반환 값

새로 생성된 NodeIterator.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또 보기

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

지정된 노드를 루트로 하는 서브트리에서 새로운 NodeIterator를 생성합니다.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 루트 | Node | 자식과 함께 반복될 노드. 이터레이터는 처음에 이 노드 바로 앞에 위치합니다. whatToShow 플래그와 필터(있는 경우)는 이 위치를 설정할 때 고려되지 않습니다. 루트는 null이면 안 됩니다. |
| whatToShow | Int64 | 플래그는 이터레이터가 제공하는 트리의 논리적 뷰에 나타날 수 있는 노드 유형을 지정합니다. 가능한 SHOW_ 값들의 집합은 NodeFilter 설명을 참고하십시오. 이러한 플래그는 OR 연산으로 결합할 수 있습니다. |

### 반환 값

새로 생성된 NodeIterator.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또 보기

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

지정된 노드를 루트로 하는 서브트리에서 새로운 NodeIterator를 생성합니다.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 루트 | Node | 자식과 함께 반복될 노드. 이터레이터는 처음에 이 노드 바로 앞에 위치합니다. whatToShow 플래그와 필터(있는 경우)는 이 위치를 설정할 때 고려되지 않습니다. 루트는 null이면 안 됩니다. |
| whatToShow | Int64 | 플래그는 이터레이터가 제공하는 트리의 논리적 뷰에 나타날 수 있는 노드 유형을 지정합니다. 가능한 SHOW_ 값들의 집합은 NodeFilter 설명을 참고하십시오. 이러한 플래그는 OR 연산으로 결합할 수 있습니다. |
| 필터 | INodeFilter | 이 TreeWalker와 함께 사용할 NodeFilter, 또는 필터가 없음을 나타내는 null. |

### 반환 값

새로 생성된 NodeIterator.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또 보기

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
