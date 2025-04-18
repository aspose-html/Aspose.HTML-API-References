---
title: MarkdownSyntaxToken Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxToken class. Represent the Markdown Syntax Token
type: docs
weight: 5470
url: /net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken/
---
## MarkdownSyntaxToken class

Represent the Markdown Syntax Token.

```csharp
public sealed class MarkdownSyntaxToken : MarkdownSyntaxNode
```

## Properties

| Name | Description |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Get the first child. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Get the last child. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Get ghe next sibling. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Get the parent node. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Get the previous sibling. |
| [Source](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken/source/) { get; } | Get the source text. |
| [Span](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken/span/) { get; } | Get the span. |
| [Text](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken/text/) { get; } | Get the text content of span. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/accept/)(*[MarkdownSyntaxVisitor](../markdownsyntaxvisitor/)*) | Accept the visitor. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(*[MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Append child node. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Get the child nodes collection. |
| [GetFullText](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken/getfulltext/)() | Defines the interface for get the full text. |
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

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)
