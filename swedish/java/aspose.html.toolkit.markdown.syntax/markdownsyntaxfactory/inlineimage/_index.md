---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Aspose.HTML för Java API-referens"
description: "MarkdownSyntaxFactory-metod. Skapar InlineImageSyntaxNode"
type: docs

url: /sv/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

Skapar [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| altText | String | Den alternativa texten. |
| href | String | Bildens URL. |
| titel | String | Titeln. |

### Returvärde

Den InlineImageSyntax.

### Se även

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

Skapar [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Den contentOpening. |
| contentClosing | MarkdownSyntaxToken | Den contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Den declarationOpening. |
| destination | LinkDestinationSyntaxNode | Destinationen. |
| titel | LinkTitleSyntaxNode | Titeln. |
| declarationClosing | MarkdownSyntaxToken | Den declarationClosing. |

### Returvärde

Den InlineImageSyntax.

### Se även

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
