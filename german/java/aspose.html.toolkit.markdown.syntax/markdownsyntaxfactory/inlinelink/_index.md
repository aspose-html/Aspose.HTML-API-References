---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Aspose.HTML für Java API-Referenz"
description: "MarkdownSyntaxFactory Methode. Erstellt InlineLinkSyntaxNode"
type: docs

url: /de/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Erstellt [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Das contentOpening. |
| contentClosing | MarkdownSyntaxToken | Das contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Das declarationOpening. |
| Ziel | LinkDestinationSyntaxNode | Das Ziel. |
| Titel | LinkTitleSyntaxNode | Der Titel. |
| declarationClosing | MarkdownSyntaxToken | Das declarationClosing. |

### Rückgabewert

Der InlineLinkSyntax.

### Siehe auch

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Erstellt InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | String | Der Linktext. |
| Ziel | String | Der String-Ziel. |
| Titel | String | Der String-Titel. |

### Rückgabewert

Der LinkReferenceDefinitionSyntax.

### Siehe auch

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
