---
title: MarkdownSyntaxFactory.InlineImage
second_title: Aspose.HTML for Java API Reference
description: MarkdownSyntaxFactory method. Creates InlineImageSyntaxNode
type: docs
weight: 210
url: /net/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

Creates [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
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
* package [com.aspose.html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

Creates [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
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
* package [com.aspose.html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* package [Aspose.HTML](../../../)
