---
title: TableRowSyntaxNode Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.TableRowSyntaxNode class. The table row syntax node
type: docs
weight: 5840
url: /net/aspose.html.toolkit.markdown.syntax/tablerowsyntaxnode/
---
## TableRowSyntaxNode class

The table row syntax node.

```csharp
public class TableRowSyntaxNode : LeafBlockSyntaxNode
```

## Properties

| Name | Description |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Get the first child. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Get the last child. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Get ghe next sibling. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Get the parent node. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Get the previous sibling. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(*[MarkdownSyntaxVisitor](../markdownsyntaxvisitor/)*) | Defines the interface for accept visitor. |
| [AppendCell](../../aspose.html.toolkit.markdown.syntax/tablerowsyntaxnode/appendcell/)(*[TableCellSyntaxNode](../tablecellsyntaxnode/)*) | Defines the interface for append of the cell. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(*[MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Append child node. |
| [AppendDelimiter](../../aspose.html.toolkit.markdown.syntax/tablerowsyntaxnode/appenddelimiter/)(*[TableDelimiterSyntaxNode](../tabledelimitersyntaxnode/)*) | Defines the interface for append delimiter. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Get the child nodes collection. |
| [GetCells](../../aspose.html.toolkit.markdown.syntax/tablerowsyntaxnode/getcells/)() | Defines the interface for get cells. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Get the leading trivia. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Get the syntax tree. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Get the Trailing trivia. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(*[MarkdownSyntaxNode](../markdownsyntaxnode/), [MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Insert before node. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(*[MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Remove the child. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(*[MarkdownSyntaxNode](../markdownsyntaxnode/), [MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Replace the child node. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Override ToString method. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(*[MarkdownTextWriter](../markdowntextwriter/)*) | Write to MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(*TextWriter*) | Write nodes to text writer. |

### See Also

* class [LeafBlockSyntaxNode](../leafblocksyntaxnode/)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)
