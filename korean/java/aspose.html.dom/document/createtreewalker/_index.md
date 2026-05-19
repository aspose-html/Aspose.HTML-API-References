---
title: "Document.CreateTreeWalker"
second_title: "Aspose.HTML for Java API 참조"
description: "Document 메서드. 지정된 노드를 루트로 하는 서브트리 위에 새로운 TreeWalker를 생성합니다"
type: docs

url: /ko/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

지정된 노드를 루트로 하는 서브트리에서 새로운 TreeWalker를 생성합니다.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 루트 | Node | TreeWalker의 루트가 될 노드. whatToShow 플래그와 NodeFilter는 이 값을 설정할 때 고려되지 않으며, 모든 노드 유형이 루트로 허용됩니다. TreeWalker의 currentNode는 이 노드로 초기화되며, 보이든 보이지 않든 관계없습니다. 루트는 parentNode 및 nextNode와 같이 문서 구조를 위로 탐색하는 메서드의 중단점 역할을 합니다. 루트는 null이면 안 됩니다. |

### 반환 값

새로 생성된 TreeWalker.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또 보기

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

지정된 노드를 루트로 하는 서브트리에서 새로운 TreeWalker를 생성합니다.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 루트 | Node | TreeWalker의 루트가 될 노드. whatToShow 플래그와 NodeFilter는 이 값을 설정할 때 고려되지 않으며, 모든 노드 유형이 루트로 허용됩니다. TreeWalker의 currentNode는 이 노드로 초기화되며, 보이든 보이지 않든 관계없습니다. 루트는 parentNode 및 nextNode와 같이 문서 구조를 위로 탐색하는 메서드의 중단점 역할을 합니다. 루트는 null이면 안 됩니다. |
| whatToShow | Int64 | flag는 트리 워커가 제시하는 트리의 논리적 보기에서 나타날 수 있는 노드 유형을 지정합니다. 가능한 SHOW_ 값 집합에 대한 설명은 NodeFilter를 참조하십시오. 이러한 플래그는 OR을 사용하여 결합할 수 있습니다. |

### 반환 값

새로 생성된 TreeWalker.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또 보기

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

지정된 노드를 루트로 하는 서브트리에서 새로운 TreeWalker를 생성합니다.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 루트 | Node | TreeWalker의 루트가 될 노드. whatToShow 플래그와 NodeFilter는 이 값을 설정할 때 고려되지 않으며, 모든 노드 유형이 루트로 허용됩니다. TreeWalker의 currentNode는 이 노드로 초기화되며, 보이든 보이지 않든 관계없습니다. 루트는 parentNode 및 nextNode와 같이 문서 구조를 위로 탐색하는 메서드의 중단점 역할을 합니다. 루트는 null이면 안 됩니다. |
| whatToShow | Int64 | flag는 트리 워커가 제시하는 트리의 논리적 보기에서 나타날 수 있는 노드 유형을 지정합니다. 가능한 SHOW_ 값 집합에 대한 설명은 NodeFilter를 참조하십시오. 이러한 플래그는 OR을 사용하여 결합할 수 있습니다. |
| 필터 | INodeFilter | 이 TreeWalker와 함께 사용할 NodeFilter, 또는 필터가 없음을 나타내는 null. |

### 반환 값

새로 생성된 TreeWalker.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또 보기

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
