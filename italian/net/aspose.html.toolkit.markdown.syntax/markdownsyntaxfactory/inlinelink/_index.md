---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML per riferimento API .NET
description: MarkdownSyntaxFactory metodo. Crea oggetti utilizzando InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /it/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Crea oggetti utilizzando InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Il contenutoApertura. |
| contentClosing | MarkdownSyntaxToken | Il contenutoChiusura. |
| declarationOpening | MarkdownSyntaxToken | La dichiarazioneApertura. |
| destination | LinkDestinationSyntaxNode | La destinazione. |
| title | LinkTitleSyntaxNode | Il titolo. |
| declarationClosing | MarkdownSyntaxToken | La dichiarazioneChiusura. |

### Valore di ritorno

La sintassi InlineLink.

### Guarda anche

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* spazio dei nomi [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* assemblea [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Crea InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | String | Il testo del collegamento. |
| destination | String | La destinazione della stringa. |
| title | String | Il titolo della stringa. |

### Valore di ritorno

La sintassi LinkReferenceDefinition.

### Guarda anche

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* spazio dei nomi [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* assemblea [Aspose.HTML](../../../)


