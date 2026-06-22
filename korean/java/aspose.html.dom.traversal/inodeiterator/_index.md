---
title: "INodeIterator 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.traversal.INodeIterator 인터페이스. 반복자는 예를 들어 NodeList의 노드 집합, 특정 Node가 관리하는 문서 하위 트리, 쿼리 결과 또는 기타 노드 집합을 순회하는 데 사용됩니다. 순회할 노드 집합은 NodeIterator 구현에 의해 결정됩니다. DOM Level 2는 문서 순서 하위 트리 순회를 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal .createNodeIterator를 호출하여 생성됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

반복자는 NodeList의 노드 집합, 특정 노드가 관리하는 문서 서브트리, 쿼리 결과 또는 기타 노드 집합과 같이 노드 집합을 순차적으로 탐색하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator 구현에 의해 결정됩니다. DOM Level 2는 문서 순서대로 서브트리를 순회하기 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal.createNodeIterator()를 호출하여 생성됩니다.

또한 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)를 참조하십시오. @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) 이 플래그의 값은 엔터티 참조 노드의 자식이 반복자에게 보이는지를 결정합니다. false인 경우 해당 노드와 그 하위 노드가 거부됩니다. 이 거부는 whatToShow 및 필터보다 우선합니다. 또한 현재 NodeIterators가 개별 노드를 건너뛰는 대신 전체 하위 트리를 거부할 수 있는 유일한 상황임을 유의하십시오. 엔터티 참조가 확장된 문서 뷰를 만들고 엔터티 참조 노드 자체를 노출하지 않으려면 whatToShow 플래그를 사용하여 엔터티 참조 노드를 숨기고 반복자를 만들 때 expandEntityReferences를 true로 설정하십시오. 엔터티 참조 노드는 포함하지만 확장은 하지 않는 뷰를 만들려면 whatToShow 플래그를 사용하여 엔터티 참조 노드를 표시하고 expandEntityReferences를 false로 설정하십시오. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) 현재 참조 노드. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | NodeIterator를 순회했던 집합에서 분리하여 모든 계산 자원을 해제하고 반복자를 INVALID 상태로 전환합니다. detach가 호출된 후 nextNode 또는 previousNode를 호출하면 INVALID_STATE_ERR 예외가 발생합니다. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | 집합에서 다음 노드를 반환하고 반복자의 위치를 집합 내에서 앞으로 이동시킵니다. NodeIterator가 생성된 후 첫 번째 nextNode() 호출은 집합의 첫 번째 노드를 반환합니다. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | 집합에서 이전 노드를 반환하고 NodeIterator의 위치를 집합 내에서 뒤로 이동시킵니다. |

### 또 보기

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
