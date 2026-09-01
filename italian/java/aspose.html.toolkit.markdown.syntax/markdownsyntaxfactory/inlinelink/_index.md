---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo MarkdownSyntaxFactory. Crea InlineLinkSyntaxNode"
type: docs

url: /it/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Crea [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Il contentOpening. |
| contentClosing | MarkdownSyntaxToken | Il contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Il declarationOpening. |
| destination | LinkDestinationSyntaxNode | La destination. |
| titolo | LinkTitleSyntaxNode | Il titolo. |
| declarationClosing | MarkdownSyntaxToken | Il declarationClosing. |

### Valore di ritorno

Il InlineLinkSyntax.

### Vedi anche

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | String | Il testo del collegamento. |
| destination | String | La destinazione String. |
| titolo | String | Il titolo String. |

### Valore di ritorno

Il LinkReferenceDefinitionSyntax.

### Vedi anche

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
