---
title: Class MarkdownSyntaxTree
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree 수업. 마크다운 구문 트리를 나타냅니다.
type: docs
weight: 5220
url: /ko/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

마크다운 구문 트리를 나타냅니다.

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | MarkdownSyntaxTree를 생성했습니다. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | MarkdownSyntaxTree 를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | 첫 아이를 얻습니다. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | 마지막 자식을 얻습니다. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | 다음 형제를 가져옵니다. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | 상위 노드를 가져옵니다. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | 이전 형제를 가져옵니다. |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | SyntaxFactory를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | 구문 트리의 방문 노드에 대한 인터페이스를 정의합니다. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 자식 노드 추가. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 자식 노드 컬렉션을 가져옵니다. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | 노드 반복자 생성을 위한 인터페이스를 정의합니다. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | 노드 반복자 생성을 위한 인터페이스를 정의합니다. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | 노드 반복자 생성을 위한 인터페이스를 정의합니다. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | 트리 워커를 만들기 위한 인터페이스를 정의합니다. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | 트리 워커를 만들기 위한 인터페이스를 정의합니다. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | 트리 워커를 만들기 위한 인터페이스를 정의합니다. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 주요 상식을 알아보세요. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 구문 트리를 가져옵니다. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 후행 퀴즈를 가져옵니다. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 노드 앞에 삽입합니다. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 자식을 제거합니다. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 하위 노드를 교체합니다. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | 구문 트리를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | 구문 트리를 지정된 경로에 저장합니다. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | 구문 트리를 지정된 작성기에 저장합니다. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString 메서드를 재정의합니다. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter. 에 쓰기 |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | 노드를 텍스트 작성기에 씁니다. |

### 또한보십시오

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* 네임스페이스 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 집회 [Aspose.HTML](../../)


