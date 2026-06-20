---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "MarkdownSyntaxFactory μέθοδος. Δημιουργεί InlineLinkSyntaxNode"
type: docs

url: /el/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Δημιουργεί [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Το contentOpening. |
| contentClosing | MarkdownSyntaxToken | Το contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Το declarationOpening. |
| προορισμός | LinkDestinationSyntaxNode | Ο προορισμός. |
| τίτλος | LinkTitleSyntaxNode | Ο τίτλος. |
| declarationClosing | MarkdownSyntaxToken | Το declarationClosing. |

### Τιμή Επιστροφής

Η InlineLinkSyntax.

### Δείτε επίσης

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Δημιουργεί InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Το κείμενο συνδέσμου. |
| προορισμός | String | Ο προορισμός String. |
| τίτλος | String | Ο τίτλος String. |

### Τιμή Επιστροφής

Η LinkReferenceDefinitionSyntax.

### Δείτε επίσης

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
