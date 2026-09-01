---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Aspose.HTML voor Java API-referentie"
description: "MarkdownSyntaxFactory-methode. Maakt InlineLinkSyntaxNode aan"
type: docs

url: /nl/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Maakt [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/) aan.

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | De contentOpening. |
| contentClosing | MarkdownSyntaxToken | De contentClosing. |
| declarationOpening | MarkdownSyntaxToken | De declarationOpening. |
| bestemming | LinkDestinationSyntaxNode | De bestemming. |
| titel | LinkTitleSyntaxNode | De titel. |
| declarationClosing | MarkdownSyntaxToken | De declarationClosing. |

### Retourwaarde

De InlineLinkSyntax.

### Zie ook

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Creëert InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | String | De linktekst. |
| bestemming | String | De String-bestemming. |
| titel | String | De String-titel. |

### Retourwaarde

De LinkReferenceDefinitionSyntax.

### Zie ook

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
