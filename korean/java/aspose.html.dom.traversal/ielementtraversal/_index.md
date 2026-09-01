---
title: "IElementTraversal 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.traversal.IElementTraversal 인터페이스. ElementTraversal 인터페이스는 문서 내 요소 간을 쉽게 탐색할 수 있도록 하는 읽기 전용 속성 집합입니다. Element Traversal을 준수하는 구현에서는 Element를 구현하는 모든 객체가 ElementTraversal 인터페이스도 구현해야 합니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal 인터페이스는 문서 내 요소 사이를 쉽게 탐색할 수 있도록 하는 읽기 전용 속성 집합입니다. Element Traversal을 준수하는 구현에서는 Element를 구현하는 모든 객체가 ElementTraversal 인터페이스도 구현해야 합니다.

```java
public interface IElementTraversal
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) 이 요소의 자식인 요소 노드 현재 개수를 반환합니다. nodeType이 1인 자식 노드가 없으면 0을 반환합니다. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) 이 요소의 첫 번째 자식 요소 노드를 반환합니다. 자식 요소가 없으면 null을 반환합니다. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) 이 요소의 마지막 자식 요소 노드를 반환합니다. 자식 요소가 없으면 null을 반환합니다. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) 이 요소의 다음 형제 요소 노드를 반환합니다. 문서 트리에서 이 요소 뒤에 오는 형제 요소 노드가 없으면 null을 반환합니다. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) 이 요소의 이전 형제 요소 노드를 반환합니다. 문서 트리에서 이 요소 앞에 오는 형제 요소 노드가 없으면 null을 반환합니다. |

### 또 보기

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
