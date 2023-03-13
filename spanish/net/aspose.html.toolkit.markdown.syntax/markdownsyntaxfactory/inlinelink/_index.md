---
title: MarkdownSyntaxFactory.InlineLink
second_title: Referencia de API de Aspose.HTML para .NET
description: MarkdownSyntaxFactory método. Crea objetos usando InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /es/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Crea objetos usando InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | El contenidoApertura. |
| contentClosing | MarkdownSyntaxToken | El contenidoCierre. |
| declarationOpening | MarkdownSyntaxToken | La declaraciónOpening. |
| destination | LinkDestinationSyntaxNode | El destino. |
| title | LinkTitleSyntaxNode | El título. |
| declarationClosing | MarkdownSyntaxToken | La declaraciónCierre. |

### Valor_devuelto

La sintaxis de InlineLink.

### Ver también

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* espacio de nombres [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* asamblea [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Crea InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| text | String | El texto del enlace. |
| destination | String | El destino de la cadena. |
| title | String | El título de la cadena. |

### Valor_devuelto

La sintaxis de definición de referencia de enlace.

### Ver también

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* espacio de nombres [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* asamblea [Aspose.HTML](../../../)


