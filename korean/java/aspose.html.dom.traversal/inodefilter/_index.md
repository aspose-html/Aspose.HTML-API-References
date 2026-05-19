---
title: "INodeFilter 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.traversal.INodeFilter 인터페이스. 필터는 노드를 걸러내는 방법을 아는 객체입니다. NodeIterator 또는 TreeWalker에 NodeFilter가 제공되면 다음 노드를 반환하기 전에 필터를 적용합니다. 필터가 노드를 허용한다고 판단하면 순회 로직이 해당 노드를 반환하고, 그렇지 않으면 다음 노드를 찾아 거부된 노드가 존재하지 않은 것처럼 처리합니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filters는 노드를 \"필터링\"하는 방법을 알고 있는 객체입니다. NodeIterator나 TreeWalker에 NodeFilter가 제공되면, 다음 노드를 반환하기 전에 필터를 적용합니다. 필터가 노드를 허용한다고 하면 순회 로직이 해당 노드를 반환하고, 그렇지 않으면 순회는 다음 노드를 찾아 거부된 노드가 없었던 것처럼 처리합니다.

DOM은 필터를 제공하지 않습니다. NodeFilter는 사용자가 직접 구현하여 자체 필터를 제공할 수 있는 인터페이스일 뿐입니다.

NodeFilter는 노드 간을 어떻게 순회하는지 알 필요도 없고, 순회되는 데이터 구조에 대해 알 필요도 없습니다. 따라서 필터를 작성하기가 매우 쉽습니다. 필터가 해야 할 일은 단일 노드를 평가하는 것뿐이기 때문입니다. 하나의 필터를 여러 종류의 순회와 함께 사용할 수 있어 코드 재사용을 촉진합니다.

또한 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)을 참조하십시오. @since DOM Level 2

```java
public interface INodeFilter
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | TreeWalker 또는 NodeIterator의 논리적 뷰에서 지정된 노드가 보이는지 테스트합니다. 이 함수는 TreeWalker와 NodeIterator 구현에 의해 호출되며, 일반적으로 사용자 코드에서 직접 호출되지 않습니다. (동일한 필터를 사용해 자체 애플리케이션 로직을 안내하고 싶다면 직접 호출할 수도 있습니다.) |

### 또 보기

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
