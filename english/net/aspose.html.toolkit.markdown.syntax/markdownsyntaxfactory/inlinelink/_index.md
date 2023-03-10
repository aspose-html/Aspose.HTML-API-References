---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML for .NET API Reference
description: MarkdownSyntaxFactory method. Creates objects using InlineLinkSyntax.CreateInstance
type: docs
weight: 220
url: /net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Creates objects using InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | The contentOpening. |
| contentClosing | MarkdownSyntaxToken | The contentClosing. |
| declarationOpening | MarkdownSyntaxToken | The declarationOpening. |
| destination | LinkDestinationSyntaxNode | The destination. |
| title | LinkTitleSyntaxNode | The title. |
| declarationClosing | MarkdownSyntaxToken | The declarationClosing. |

### Return Value

The InlineLinkSyntax.

### See Also

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* assembly [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Creates InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| text | String | The link text. |
| destination | String | The string destination. |
| title | String | The string title. |

### Return Value

The LinkReferenceDefinitionSyntax.

### See Also

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* assembly [Aspose.HTML](../../../)
