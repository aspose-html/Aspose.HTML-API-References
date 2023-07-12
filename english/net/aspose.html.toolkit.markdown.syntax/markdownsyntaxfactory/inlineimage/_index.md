---
title: MarkdownSyntaxFactory.InlineImage
second_title: Aspose.HTML for .NET API Reference
description: MarkdownSyntaxFactory method. Creates InlineImageSyntaxNode
type: docs
weight: 210
url: /net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(string, string, string) {#inlineimage_1}

Creates [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```csharp
public InlineImageSyntaxNode InlineImage(string altText, string href, string title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| altText | String | The alternative text. |
| href | String | The URL of image. |
| title | String | The title. |

### Return Value

The InlineImageSyntax.

### See Also

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

Creates [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```csharp
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
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

The InlineImageSyntax.

### See Also

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../../)
