---
title: MarkdownSyntaxTree Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree class. Represent the Markdown Syntax Tree
type: docs
weight: 5220
url: /java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Represent the Markdown Syntax Tree.

```java
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## Constructors

| Name | Description |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | Created the MarkdownSyntaxTree. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | Creates the MarkdownSyntaxTree |

## Properties

| Name | Description |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) Get the first child. |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) Get the last child. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) Get ghe next sibling. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) Get the parent node. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) Get the previous sibling. |
| [getSyntaxFactory](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) Get the SyntaxFactory. |

## Methods

| Name | Description |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | Defines the interface for visiting nodes of the syntax tree. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Append child node. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Get the child nodes collection. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | Defines the interface for create of the node iterator. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | Defines the interface for create of the node iterator. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Defines the interface for create of the node iterator. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | Defines the interface for create the tree walker. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | Defines the interface for create the tree walker. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Defines the interface for create the tree walker. |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Get the leading trivia. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Get the syntax tree. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Get the Trailing trivia. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Insert before node. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Remove the child. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Replace the child node. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | Saves the syntax tree to the specified stream. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(String) | Saves the syntax tree to the specified path. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | Saves the syntax tree to the specified writer. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | Override ToString method. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Write to MarkdownTextWriter. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Write nodes to text writer. |

### See Also

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.Toolkit.Markdown.Syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
