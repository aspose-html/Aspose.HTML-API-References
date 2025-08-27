---
title: MarkdownBlockParser Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.Parser.MarkdownBlockParser class. Defines the base class MarkdownBlockParser
type: docs
weight: 5730
url: /net/aspose.html.toolkit.markdown.syntax.parser/markdownblockparser/
---
## MarkdownBlockParser class

Defines the base class MarkdownBlockParser

```csharp
public abstract class MarkdownBlockParser
```

## Methods

| Name | Description |
| --- | --- |
| virtual [CanClose](../../aspose.html.toolkit.markdown.syntax.parser/markdownblockparser/canclose/)(*[BlockSyntaxDescriptor](../blocksyntaxdescriptor/), [BlockClosingReason](../blockclosingreason/), [IBlockParsingContext](../iblockparsingcontext/)*) | Defines interface for CanClose method. |
| abstract [CanParse](../../aspose.html.toolkit.markdown.syntax.parser/markdownblockparser/canparse/)(*[IBlockParsingContext](../iblockparsingcontext/)*) | Defines interface for get the CanParse value. |
| virtual [Continue](../../aspose.html.toolkit.markdown.syntax.parser/markdownblockparser/continue/)(*[BlockSyntaxDescriptor](../blocksyntaxdescriptor/), [IBlockParsingContext](../iblockparsingcontext/)*) | Defines the interface for Continue |
| virtual [OnClose](../../aspose.html.toolkit.markdown.syntax.parser/markdownblockparser/onclose/)(*[BlockSyntaxDescriptor](../blocksyntaxdescriptor/), [MarkdownSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/), [IBlockParsingContext](../iblockparsingcontext/)*) | Defines interface for OnClose method. |
| virtual [OnOpen](../../aspose.html.toolkit.markdown.syntax.parser/markdownblockparser/onopen/)(*[BlockSyntaxDescriptor](../blocksyntaxdescriptor/), [IBlockParsingContext](../iblockparsingcontext/)*) | Defines interface for OnOpen method. |
| virtual [OnProcessInline](../../aspose.html.toolkit.markdown.syntax.parser/markdownblockparser/onprocessinline/)(*[BlockSyntaxDescriptor](../blocksyntaxdescriptor/), [IBlockParsingContext](../iblockparsingcontext/)*) | Defines the interface for OnProcessInline method. |
| abstract [Parse](../../aspose.html.toolkit.markdown.syntax.parser/markdownblockparser/parse/)(*[IBlockParsingContext](../iblockparsingcontext/)*) | Defines interface for parse ofr the context.. |

### See Also

* namespace [Aspose.Html.Toolkit.Markdown.Syntax.Parser](../../aspose.html.toolkit.markdown.syntax.parser/)
* assembly [Aspose.HTML](../../)
