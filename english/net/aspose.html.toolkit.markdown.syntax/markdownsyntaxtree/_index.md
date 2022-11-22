---
title: MarkdownSyntaxTree
second_title: Aspose.HTML for .NET API Reference
description: Represent the Markdown Syntax Tree.
type: docs
weight: 5220
url: /net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Represent the Markdown Syntax Tree.

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## Constructors

| Name | Description |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree#constructor)() | Created the MarkdownSyntaxTree. |
| [MarkdownSyntaxTree](markdownsyntaxtree#constructor_1)(Configuration) | Creates the MarkdownSyntaxTree |

## Properties

| Name | Description |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Get the first child. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Get the last child. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Get ghe next sibling. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Get the parent node. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Get the previous sibling. |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | Get the SyntaxFactory. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | Defines the interface for visiting nodes of the syntax tree. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Append child node. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Get the child nodes collection. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | Defines the interface for create of the node iterator. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | Defines the interface for create of the node iterator. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Defines the interface for create of the node iterator. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | Defines the interface for create the tree walker. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | Defines the interface for create the tree walker. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Defines the interface for create the tree walker. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Get the leading trivia. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Get the syntax tree. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Get the Trailing trivia. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Insert before node. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Remove the child. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Replace the child node. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | Saves the syntax tree to the specified stream. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | Saves the syntax tree to the specified path. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | Saves the syntax tree to the specified writer. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Override ToString method. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Write to MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Write nodes to text writer. |

### See Also

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
