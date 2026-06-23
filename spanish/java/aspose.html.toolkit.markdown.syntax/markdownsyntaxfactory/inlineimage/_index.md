---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "MarkdownSyntaxFactory método. Crea InlineImageSyntaxNode"
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
| altText | Cadena | El texto alternativo. |
| href | Cadena | La URL de la imagen. |
| title | Cadena | El título. |

### Valor devuelto

The InlineImageSyntax.

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
| contentOpening | MarkdownSyntaxToken | The contentOpening. |
| contentClosing | MarkdownSyntaxToken | The contentClosing. |
| declarationOpening | MarkdownSyntaxToken | The declarationOpening. |
| destino | LinkDestinationSyntaxNode | El destino. |
| title | LinkTitleSyntaxNode | El título. |
| declarationClosing | MarkdownSyntaxToken | El declarationClosing. |

### Valor devuelto

The InlineImageSyntax.

### Ver también

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
