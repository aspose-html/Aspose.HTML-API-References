---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método MarkdownSyntaxFactory. Crea InlineLinkSyntaxNode"
type: docs

url: /es/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Crea [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
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

El InlineLinkSyntax.

### Ver también

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Crea InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | Cadena | El texto del enlace. |
| destino | Cadena | El destino de cadena. |
| title | Cadena | El título de cadena. |

### Valor devuelto

El LinkReferenceDefinitionSyntax.

### Ver también

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
