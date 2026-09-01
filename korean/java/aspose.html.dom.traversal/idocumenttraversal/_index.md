---
title: "IDocumentTraversal 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.traversal.IDocumentTraversal 인터페이스. DocumentTraversal은 반복자와 트리 워커를 생성하여 노드와 그 자식을 문서 순서 깊이 우선 사전 순으로 탐색하는 메서드를 포함합니다. 이는 문서의 텍스트 표현에서 시작 태그가 나타나는 순서와 동일합니다. Traversal 기능을 지원하는 DOM에서는 DocumentTraversal이 Document 인터페이스를 구현하는 객체와 동일하게 구현됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal은 노드와 그 자식을 문서 순서(깊이 우선, 전위 순회)대로 순회하기 위한 반복자와 트리 워커를 생성하는 메서드를 포함합니다(이는 문서의 텍스트 표현에서 시작 태그가 나타나는 순서와 동일합니다). Traversal 기능을 지원하는 DOM에서는 DocumentTraversal이 Document 인터페이스를 구현하는 동일한 객체에 의해 구현됩니다.

또한 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)를 참조하십시오. @since DOM Level 2

```java
public interface IDocumentTraversal
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | 지정된 노드를 루트로 하는 하위 트리에서 새로운 NodeIterator를 생성합니다. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | 지정된 노드를 루트로 하는 하위 트리에서 새로운 NodeIterator를 생성합니다. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | 지정된 노드를 루트로 하는 하위 트리에서 새로운 NodeIterator를 생성합니다. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | 지정된 노드를 루트로 하는 하위 트리에서 새로운 TreeWalker를 생성합니다. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | 지정된 노드를 루트로 하는 하위 트리에서 새로운 TreeWalker를 생성합니다. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | 지정된 노드를 루트로 하는 하위 트리에서 새로운 TreeWalker를 생성합니다. |

### 또 보기

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
