---
title: HugoFrontMatterSyntaxNode Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.Extensions.HugoFrontMatterSyntaxNode class. Defines the base class HugoFrontMatterSyntaxNode
type: docs
weight: 5170
url: /net/aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/
---
## HugoFrontMatterSyntaxNode class

Defines the base class HugoFrontMatterSyntaxNode

```csharp
public abstract class HugoFrontMatterSyntaxNode : BlockSyntaxNode
```

## Public Members
## Properties

| Name | Description |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Get the first child. |
| abstract [FrontMatterRootNode](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/frontmatterrootnode/) { get; } | Get and set the RootNode |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Get the last child. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Get ghe next sibling. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Get the parent node. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Get the previous sibling. |

## Public Members
## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(*[MarkdownSyntaxVisitor](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/)*) | Defines the interface for accept visitor. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(*[MarkdownSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/)*) | Append child node. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Get the child nodes collection. |
| [Find](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find)(*params string[]*) | Defines the interface for find BaseSyntaxNode |
| abstract [Find&lt;T&gt;](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find_1)(*params string[]*) | Defines the interface for find T |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Get the leading trivia. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Get the syntax tree. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Get the Trailing trivia. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(*[MarkdownSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/), [MarkdownSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/)*) | Insert before node. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(*[MarkdownSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/)*) | Remove the child. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(*[MarkdownSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/), [MarkdownSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/)*) | Replace the child node. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Override ToString method. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(*[MarkdownTextWriter](../../aspose.html.toolkit.markdown.syntax/markdowntextwriter/)*) | Write to MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(*TextWriter*) | Write nodes to text writer. |

### See Also

* class [BlockSyntaxNode](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax.Extensions](../../aspose.html.toolkit.markdown.syntax.extensions/)
* assembly [Aspose.HTML](../../)
