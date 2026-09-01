---
title: "MarkdownSyntaxTree 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxTree 클래스. Markdown 구문 트리를 나타냅니다"
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Markdown 구문 트리를 나타냅니다.

```java
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | MarkdownSyntaxTree를 생성했습니다. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | MarkdownSyntaxTree를 생성합니다 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) 첫 번째 자식을 가져옵니다. |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) 마지막 자식을 가져옵니다. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) 다음 형제를 가져옵니다. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) 부모 노드를 가져옵니다. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) 이전 형제를 가져옵니다. |
| [getSyntaxFactory](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) SyntaxFactory를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | 구문 트리 노드를 방문하기 위한 인터페이스를 정의합니다. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 자식 노드를 추가합니다. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 자식 노드 컬렉션을 가져옵니다. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | 노드 반복자를 생성하기 위한 인터페이스를 정의합니다. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | 노드 반복자를 생성하기 위한 인터페이스를 정의합니다. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | 노드 반복자를 생성하기 위한 인터페이스를 정의합니다. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | 트리 워커를 생성하기 위한 인터페이스를 정의합니다. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | 트리 워커를 생성하기 위한 인터페이스를 정의합니다. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | 트리 워커를 생성하기 위한 인터페이스를 정의합니다. |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 선행 트리비아를 가져옵니다. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 구문 트리를 가져옵니다. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 후행 트리비아를 가져옵니다. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 노드 앞에 삽입합니다. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 자식을 제거합니다. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 자식 노드를 교체합니다. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | 구문 트리를 지정된 스트림에 저장합니다. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(String) | 구문 트리를 지정된 경로에 저장합니다. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | 구문 트리를 지정된 라이터에 저장합니다. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | ToString 메서드를 재정의합니다. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter에 씁니다. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | 노드를 텍스트 라이터에 씁니다. |

### 또 보기

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
