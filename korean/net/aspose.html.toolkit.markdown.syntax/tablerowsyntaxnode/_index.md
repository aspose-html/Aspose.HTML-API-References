---
title: Class TableRowSyntaxNode
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Toolkit.Markdown.Syntax.TableRowSyntaxNode 수업. 테이블 행 구문 node.
type: docs
weight: 5580
url: /ko/net/aspose.html.toolkit.markdown.syntax/tablerowsyntaxnode/
---
## TableRowSyntaxNode class

테이블 행 구문 node.

```csharp
public class TableRowSyntaxNode : LeafBlockSyntaxNode
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | 첫 아이를 얻습니다. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | 마지막 자식을 얻습니다. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | 다음 형제를 가져옵니다. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | 상위 노드를 가져옵니다. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | 이전 형제를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | 방문자 수락을 위한 인터페이스를 정의합니다. |
| [AppendCell](../../aspose.html.toolkit.markdown.syntax/tablerowsyntaxnode/appendcell/)(TableCellSyntaxNode) | 셀 추가를 위한 인터페이스를 정의합니다. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 자식 노드 추가. |
| [AppendDelimiter](../../aspose.html.toolkit.markdown.syntax/tablerowsyntaxnode/appenddelimiter/)(TableDelimiterSyntaxNode) | 추가 구분 기호에 대한 인터페이스를 정의합니다. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 자식 노드 컬렉션을 가져옵니다. |
| [GetCells](../../aspose.html.toolkit.markdown.syntax/tablerowsyntaxnode/getcells/)() | 셀 가져오기에 대한 인터페이스를 정의합니다. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 주요 상식을 알아보세요. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 구문 트리를 가져옵니다. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 후행 퀴즈를 가져옵니다. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 노드 앞에 삽입합니다. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 자식을 제거합니다. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 하위 노드를 교체합니다. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString 메서드를 재정의합니다. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter. 에 쓰기 |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | 노드를 텍스트 작성기에 씁니다. |

### 또한보십시오

* class [LeafBlockSyntaxNode](../leafblocksyntaxnode/)
* 네임스페이스 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 집회 [Aspose.HTML](../../)


