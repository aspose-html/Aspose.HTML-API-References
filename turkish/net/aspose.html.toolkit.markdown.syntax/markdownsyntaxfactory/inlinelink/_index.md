---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML for .NET API Referansı
description: MarkdownSyntaxFactory yöntem. InlineLinkSyntax.CreateInstance. kullanarak nesneler oluşturur
type: docs
weight: 220
url: /tr/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

InlineLinkSyntax.CreateInstance. kullanarak nesneler oluşturur

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | içerikAçılış. |
| contentClosing | MarkdownSyntaxToken | İçerik Kapanıyor. |
| declarationOpening | MarkdownSyntaxToken | Beyanname Açılıyor. |
| destination | LinkDestinationSyntaxNode | Hedef. |
| title | LinkTitleSyntaxNode | Başlık. |
| declarationClosing | MarkdownSyntaxToken | Bildirim Kapanıyor. |

### Geri dönüş değeri

InlineLink Sözdizimi.

### Ayrıca bakınız

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* ad alanı [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* toplantı [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

InlineLink. oluşturur

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| text | String | Bağlantı metni. |
| destination | String | Dize hedefi. |
| title | String | Dize başlığı. |

### Geri dönüş değeri

LinkReferenceDefinitionSyntax.

### Ayrıca bakınız

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* ad alanı [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* toplantı [Aspose.HTML](../../../)


