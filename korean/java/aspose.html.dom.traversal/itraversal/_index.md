---
title: "ITraversal Interface"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.traversal.ITraversal 인터페이스. 반복자는 NodeList에 있는 노드 집합, 특정 Node가 관리하는 문서 서브트리, 쿼리 결과 또는 기타 노드 집합 등 노드 집합을 순차적으로 탐색하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator 구현에 의해 결정됩니다. DOM Level 2는 문서 순서대로 서브트리를 순회하기 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal.createNodeIterator를 호출하여 생성됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

반복자는 NodeList의 노드 집합, 특정 노드가 관리하는 문서 서브트리, 쿼리 결과 또는 기타 노드 집합과 같이 노드 집합을 순차적으로 탐색하는 데 사용됩니다. 반복할 노드 집합은 NodeIterator 구현에 의해 결정됩니다. DOM Level 2는 문서 순서대로 서브트리를 순회하기 위한 단일 NodeIterator 구현을 지정합니다. 이러한 반복자의 인스턴스는 DocumentTraversal.createNodeIterator()를 호출하여 생성됩니다.

또한 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)를 참조하십시오. @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) 노드를 필터링하는 데 사용되는 NodeFilter입니다. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) 생성 시 지정된 NodeIterator의 루트 노드입니다. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) 이 속성은 반복자를 통해 어떤 노드 유형이 표시될지를 결정합니다. 사용 가능한 상수 집합은 NodeFilter 인터페이스에 정의되어 있습니다. whatToShow에 의해 허용되지 않은 노드는 건너뛰지만, 그 자식 노드는 여전히 고려될 수 있습니다. 이 건너뛰기는 필터보다 우선한다는 점에 유의하십시오. |

### 또 보기

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
