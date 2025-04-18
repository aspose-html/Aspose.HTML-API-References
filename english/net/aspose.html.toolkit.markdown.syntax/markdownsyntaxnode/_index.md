---
title: MarkdownSyntaxNode Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxNode class. Base implementation of the MarkdownSyntaxNode
type: docs
weight: 5450
url: /net/aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/
---
## MarkdownSyntaxNode class

Base implementation of the MarkdownSyntaxNode.

```csharp
public abstract class MarkdownSyntaxNode : IWritable
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
| virtual [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/accept/)(*[MarkdownSyntaxVisitor](../markdownsyntaxvisitor/)*) | Accept the visitor. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(*MarkdownSyntaxNode*) | Append child node. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Get the child nodes collection. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Get the leading trivia. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Get the syntax tree. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Get the Trailing trivia. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(*MarkdownSyntaxNode, MarkdownSyntaxNode*) | Insert before node. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(*MarkdownSyntaxNode*) | Remove the child. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(*MarkdownSyntaxNode, MarkdownSyntaxNode*) | Replace the child node. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Override ToString method. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/#writeto)(*[MarkdownTextWriter](../markdowntextwriter/)*) | Write to MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/#writeto_1)(*TextWriter*) | Write nodes to text writer. |

### See Also

* interface [IWritable](../iwritable/)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)
