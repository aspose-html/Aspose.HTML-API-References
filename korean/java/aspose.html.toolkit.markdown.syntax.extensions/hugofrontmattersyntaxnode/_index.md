---
title: "HugoFrontMatterSyntaxNode 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.toolkit.markdown.syntax.extensions.HugoFrontMatterSyntaxNode 클래스. 기본 클래스인 HugoFrontMatterSyntaxNode를 정의합니다."
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/
---
## HugoFrontMatterSyntaxNode class

HugoFrontMatterSyntaxNode 기본 클래스를 정의합니다.

```java
public abstract class HugoFrontMatterSyntaxNode : BlockSyntaxNode
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) 첫 번째 자식을 가져옵니다. |
| abstract [getFrontMatterRootNode](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/frontmatterrootnode/) RootNode를 가져오고 설정합니다. |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) 마지막 자식을 가져옵니다. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) 다음 형제를 가져옵니다. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) 부모 노드를 가져옵니다. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) 이전 형제를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | 방문자를 수락하기 위한 인터페이스를 정의합니다. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 자식 노드를 추가합니다. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 자식 노드 컬렉션을 가져옵니다. |
| [find](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find)(params String[]) | BaseSyntaxNode 찾기를 위한 인터페이스를 정의합니다. |
| abstract [Find&lt;T&gt;](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find_1)(params String[]) | T 찾기를 위한 인터페이스를 정의합니다. |
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

* class [BlockSyntaxNode](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax.extensions](../../com.aspose.html.toolkit.markdown.syntax.extensions/)
* package [Aspose.HTML](../../)
