---
title: "InlineSyntaxNode 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.toolkit.markdown.syntax.InlineSyntaxNode 클래스. InlineSyntaxNode의 기본 구현입니다."
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax/inlinesyntaxnode/
---
## InlineSyntaxNode class

InlineSyntaxNode의 기본 구현입니다.

```java
public abstract class InlineSyntaxNode : MarkdownSyntaxNode
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) 첫 번째 자식을 가져옵니다. |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) 마지막 자식을 가져옵니다. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) 다음 형제를 가져옵니다. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) 부모 노드를 가져옵니다. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) 이전 형제를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [Accept](../../com.aspose.html.toolkit.markdown.syntax/inlinesyntaxnode/accept/)(MarkdownSyntaxVisitor) | 방문자를 수락하기 위한 인터페이스를 정의합니다. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 자식 노드를 추가합니다. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 자식 노드 컬렉션을 가져옵니다. |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 선행 트리비아를 가져옵니다. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 구문 트리를 가져옵니다. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 후행 트리비아를 가져옵니다. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 노드 앞에 삽입합니다. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 자식을 제거합니다. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 자식 노드를 교체합니다. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | ToString 메서드를 재정의합니다. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter에 씁니다. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | 노드를 텍스트 라이터에 씁니다. |

### 또 보기

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
