---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML untuk Referensi .NET API
description: MarkdownSyntaxFactory metode. Membuat objek menggunakan InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /id/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Membuat objek menggunakan InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Pembukaan konten. |
| contentClosing | MarkdownSyntaxToken | Konten Penutup. |
| declarationOpening | MarkdownSyntaxToken | DeklarasiPembukaan. |
| destination | LinkDestinationSyntaxNode | Tempat tujuan. |
| title | LinkTitleSyntaxNode | Judul. |
| declarationClosing | MarkdownSyntaxToken | Deklarasi Penutup. |

### Nilai Pengembalian

Sintaks InlineLink.

### Lihat juga

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* ruang nama [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* perakitan [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Membuat InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| text | String | Teks tautan. |
| destination | String | Tujuan string. |
| title | String | Judul string. |

### Nilai Pengembalian

LinkReferenceDefinitionSyntax.

### Lihat juga

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* ruang nama [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* perakitan [Aspose.HTML](../../../)


