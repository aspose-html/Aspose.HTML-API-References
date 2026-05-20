---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Aspose.HTML för Java API-referens"
description: "MarkdownSyntaxFactory-metoden. Skapar InlineLinkSyntaxNode"
type: docs

url: /sv/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Skapar [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Den contentOpening. |
| contentClosing | MarkdownSyntaxToken | Den contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Den declarationOpening. |
| destination | LinkDestinationSyntaxNode | Den destination. |
| titel | LinkTitleSyntaxNode | Titeln. |
| declarationClosing | MarkdownSyntaxToken | Den declarationClosing. |

### Returvärde

Den InlineLinkSyntax.

### Se även

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Skapar InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | String | Länktexten. |
| destination | String | Den String-destinationen. |
| titel | String | Den String-titeln. |

### Returvärde

Den LinkReferenceDefinitionSyntax.

### Se även

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
