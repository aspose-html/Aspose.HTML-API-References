---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Aspose.HTML für Java API-Referenz"
description: "MarkdownSyntaxFactory-Methode. Erstellt InlineImageSyntaxNode"
type: docs

url: /de/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

Erstellt [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| altText | String | Der alternative Text. |
| href | String | Die URL des Bildes. |
| Titel | String | Der Titel. |

### Rückgabewert

Die InlineImageSyntax.

### Siehe auch

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

Erstellt [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
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

Die InlineImageSyntax.

### Siehe auch

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
