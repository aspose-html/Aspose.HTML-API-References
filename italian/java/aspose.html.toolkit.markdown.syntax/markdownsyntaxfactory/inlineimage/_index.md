---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo MarkdownSyntaxFactory. Crea InlineImageSyntaxNode"
type: docs

url: /it/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

Crea [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| altText | String | Il testo alternativo. |
| href | String | L'URL dell'immagine. |
| titolo | String | Il titolo. |

### Valore di ritorno

L'InlineImageSyntax.

### Vedi anche

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

Crea [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Il contentOpening. |
| contentClosing | MarkdownSyntaxToken | Il contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Il declarationOpening. |
| destination | LinkDestinationSyntaxNode | La destinazione. |
| titolo | LinkTitleSyntaxNode | Il titolo. |
| declarationClosing | MarkdownSyntaxToken | Il declarationClosing. |

### Valore di ritorno

L'InlineImageSyntax.

### Vedi anche

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
