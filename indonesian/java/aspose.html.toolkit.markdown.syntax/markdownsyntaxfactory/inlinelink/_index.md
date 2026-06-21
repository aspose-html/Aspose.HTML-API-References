---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode MarkdownSyntaxFactory. Membuat InlineLinkSyntaxNode"
type: docs

url: /id/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Membuat [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | contentOpening. |
| contentClosing | MarkdownSyntaxToken | contentClosing. |
| declarationOpening | MarkdownSyntaxToken | declarationOpening. |
| destination | LinkDestinationSyntaxNode | destination. |
| judul | LinkTitleSyntaxNode | Judul. |
| declarationClosing | MarkdownSyntaxToken | declarationClosing. |

### Nilai Kembali

InlineLinkSyntax.

### Lihat Juga

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Membuat InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | String | Teks tautan. |
| destination | String | Tujuan String. |
| judul | String | Judul String. |

### Nilai Kembali

LinkReferenceDefinitionSyntax.

### Lihat Juga

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
