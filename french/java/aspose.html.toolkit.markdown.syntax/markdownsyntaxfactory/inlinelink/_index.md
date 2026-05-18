---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode MarkdownSyntaxFactory. Crée InlineLinkSyntaxNode"
type: docs

url: /fr/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Crée [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Le contentOpening. |
| contentClosing | MarkdownSyntaxToken | Le contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Le declarationOpening. |
| destination | LinkDestinationSyntaxNode | La destination. |
| titre | LinkTitleSyntaxNode | Le titre. |
| declarationClosing | MarkdownSyntaxToken | Le declarationClosing. |

### Valeur de retour

Le InlineLinkSyntax.

### Voir aussi

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Crée InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| texte | String | Le texte du lien. |
| destination | String | La destination de la String. |
| titre | String | Le titre de la String. |

### Valeur de retour

Le LinkReferenceDefinitionSyntax.

### Voir aussi

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
