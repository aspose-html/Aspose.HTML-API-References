---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método MarkdownSyntaxFactory. Crea InlineImageSyntaxNode"
type: docs

url: /es/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

Crea [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| altText | String | El texto alternativo. |
| href | String | La URL de la imagen. |
| title | String | El título. |

### Valor de retorno

El InlineImageSyntax.

### Ver también

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

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | El contentOpening. |
| contentClosing | MarkdownSyntaxToken | El contentClosing. |
| declarationOpening | MarkdownSyntaxToken | El declarationOpening. |
| destination | LinkDestinationSyntaxNode | El destination. |
| title | LinkTitleSyntaxNode | El título. |
| declarationClosing | MarkdownSyntaxToken | El declarationClosing. |

### Valor de retorno

El InlineImageSyntax.

### Ver también

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
