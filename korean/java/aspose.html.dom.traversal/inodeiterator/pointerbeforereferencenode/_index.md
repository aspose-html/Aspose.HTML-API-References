---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML for Java API 참조"
description: "INodeIterator 속성. 이 플래그의 값은 엔터티 참조 노드의 자식이 iterator에 표시되는지를 결정합니다. false인 경우 해당 노드와 그 하위 노드가 거부됩니다. 이 거부는 whatToShow 및 필터보다 우선합니다. 또한 현재 NodeIterators가 개별 노드를 건너뛰는 대신 전체 서브트리를 거부할 수 있는 유일한 상황임을 유의하십시오. 엔터티 참조가 확장된 문서 보기를 만들고 엔터티 참조 노드 자체를 노출하지 않으려면 whatToShow 플래그를 사용하여 엔터티 참조 노드를 숨기고 iterator를 생성할 때 expandEntityReferences를 true로 설정하십시오. 엔터티 참조 노드는 포함하지만 엔터티 확장은 하지 않는 보기를 만들려면 whatToShow 플래그를 사용하여 엔터티 참조 노드를 표시하고 expandEntityReferences를 false로 설정하십시오."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

이 플래그의 값은 엔터티 참조 노드의 자식이 iterator에 표시되는지를 결정합니다. false인 경우 해당 노드와 그 하위 노드가 거부됩니다. 이 거부는 whatToShow 및 필터보다 우선합니다. 또한 현재 NodeIterators가 개별 노드를 건너뛰는 대신 전체 서브트리를 거부할 수 있는 유일한 상황임을 유의하십시오. 엔터티 참조가 확장된 문서 보기를 만들고 엔터티 참조 노드 자체를 노출하지 않으려면 whatToShow 플래그를 사용하여 엔터티 참조 노드를 숨기고 iterator를 생성할 때 expandEntityReferences를 true로 설정하십시오. 엔터티 참조 노드는 포함하지만 엔터티 확장은 하지 않는 보기를 만들려면 whatToShow 플래그를 사용하여 엔터티 참조 노드를 표시하고 expandEntityReferences를 false로 설정하십시오.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true`이면 [expand entity references]; 그렇지 않으면 `false`.

### 또 보기

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
