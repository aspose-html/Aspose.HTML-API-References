---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML für .NET-API-Referenz
description: MarkdownSyntaxFactory methode. Erstellt Objekte mit InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /de/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Erstellt Objekte mit InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Der InhaltEröffnung. |
| contentClosing | MarkdownSyntaxToken | Der InhaltClosing. |
| declarationOpening | MarkdownSyntaxToken | Die DeklarationEröffnung. |
| destination | LinkDestinationSyntaxNode | Das Ziel. |
| title | LinkTitleSyntaxNode | Der Titel. |
| declarationClosing | MarkdownSyntaxToken | Die DeklarationClosing. |

### Rückgabewert

Die InlineLinkSyntax.

### Siehe auch

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* namensraum [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* Montage [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Erstellt InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | String | Der Linktext. |
| destination | String | Das Zeichenfolgenziel. |
| title | String | Der Titel der Zeichenfolge. |

### Rückgabewert

Die LinkReferenceDefinitionSyntax.

### Siehe auch

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* namensraum [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* Montage [Aspose.HTML](../../../)


