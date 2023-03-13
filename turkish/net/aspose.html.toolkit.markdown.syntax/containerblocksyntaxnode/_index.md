---
title: Class ContainerBlockSyntaxNode
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Toolkit.Markdown.Syntax.ContainerBlockSyntaxNode sınıf. ContainerBlockSyntaxNode. nin temel uygulaması
type: docs
weight: 4850
url: /tr/net/aspose.html.toolkit.markdown.syntax/containerblocksyntaxnode/
---
## ContainerBlockSyntaxNode class

ContainerBlockSyntaxNode. 'nin temel uygulaması

```csharp
public abstract class ContainerBlockSyntaxNode : BlockSyntaxNode
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | İlk çocuğu alın. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Son çocuğu alın. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Sonraki kardeşi alın. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Üst düğümü alın. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Önceki kardeşi alın. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Ziyaretçi kabul etmek için arayüzü tanımlar. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Alt düğümü ekle. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Alt düğüm koleksiyonunu alın. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Önde gelen önemsiz bilgileri alın. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Sözdizimi ağacını alın. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Sondaki önemsiz bilgileri edinin. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Node. 'den önce ekle |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Alt öğeyi kaldırın. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Alt düğümü değiştirin. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString yöntemini geçersiz kıl. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter. 'a Yaz |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Düğümleri metin yazıcısına yaz. |

### Ayrıca bakınız

* class [BlockSyntaxNode](../blocksyntaxnode/)
* ad alanı [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* toplantı [Aspose.HTML](../../)


