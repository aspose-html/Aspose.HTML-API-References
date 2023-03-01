---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML för .NET API Referens
description: MarkdownSyntaxFactory metod. Skapar objekt med InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /sv/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Skapar objekt med InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Innehållsöppningen. |
| contentClosing | MarkdownSyntaxToken | Innehållet Stänger. |
| declarationOpening | MarkdownSyntaxToken | Deklarationen Öppnar. |
| destination | LinkDestinationSyntaxNode | Destinationen. |
| title | LinkTitleSyntaxNode | Titeln. |
| declarationClosing | MarkdownSyntaxToken | DeklarationenStängning. |

### Returvärde

InlineLinkSyntax.

### Se även

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* namnutrymme [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* hopsättning [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Skapar InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | String | Länktexten. |
| destination | String | Strängdestinationen. |
| title | String | Strängtiteln. |

### Returvärde

LinkReferenceDefinitionSyntax.

### Se även

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* namnutrymme [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* hopsättning [Aspose.HTML](../../../)


