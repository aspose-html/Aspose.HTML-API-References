---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML για Αναφορά API .NET
description: MarkdownSyntaxFactory μέθοδος. Δημιουργεί αντικείμενα χρησιμοποιώντας InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /el/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Δημιουργεί αντικείμενα χρησιμοποιώντας InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Το περιεχόμενο Άνοιγμα. |
| contentClosing | MarkdownSyntaxToken | Το περιεχόμενο Κλείσιμο. |
| declarationOpening | MarkdownSyntaxToken | Η Διακήρυξη Έναρξης. |
| destination | LinkDestinationSyntaxNode | Ο προορισμός. |
| title | LinkTitleSyntaxNode | Ο τίτλος. |
| declarationClosing | MarkdownSyntaxToken | Η δήλωση Κλείσιμο. |

### Επιστρεφόμενη Αξία

Το InlineLinkSyntax.

### Δείτε επίσης

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* χώρος ονομάτων [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* συνέλευση [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Δημιουργεί InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Το κείμενο του συνδέσμου. |
| destination | String | Ο προορισμός εγχόρδων. |
| title | String | Ο τίτλος της χορδής. |

### Επιστρεφόμενη Αξία

Η Σύνταξη LinkReferenceDefinition.

### Δείτε επίσης

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* χώρος ονομάτων [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* συνέλευση [Aspose.HTML](../../../)


