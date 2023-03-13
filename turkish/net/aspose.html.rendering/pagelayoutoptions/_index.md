---
title: Enum PageLayoutOptions
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Rendering.PageLayoutOptions Sıralama. Diğer PageSetup seçenekleriyle birlikte sayfaların boyutlarını ve düzenlerini belirleyen bayrakları belirtir. Bu bayraklar açıklamalarına göre birleştirilebilir.
type: docs
weight: 4380
url: /tr/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Diğer PageSetup seçenekleriyle birlikte sayfaların boyutlarını ve düzenlerini belirleyen bayrakları belirtir. Bu bayraklar açıklamalarına göre birleştirilebilir.

```csharp
[Flags]
public enum PageLayoutOptions
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| None | `0` | PageLayoutOptions'ın sayfaların boyutlarını ve düzenlerini etkilemeyeceğini gösteren varsayılan değer. |
| FitToContentWidth | `1` | Bu bayrak, sayfaların genişliğinin belirtilen sayfa genişliğinden değil, içerik boyutundan belirlendiğini belirtir. İçeriğin genişliği her sayfa için ayrı ayrı hesaplanır. |
| UseWidestPage | `2` | İle birleştirildiğindeFitToContentWidth her sayfanın genişliğinin aynı olacağını ve tüm sayfalar arasında en geniş içerik boyutuna eşit olacağını belirtir. |
| FitToWidestContentWidth | `3` | Bu bayrak, sayfanın genişliğinin belirtilen sayfa genişliğinden değil, içerik boyutundan belirlendiğini belirtir. Her sayfanın genişliği aynı olacak ve tüm sayfalar arasındaki en geniş içerik boyutuna eşit olacaktır. |
| FitToContentHeight | `10` | Bu bayrak, sayfanın yüksekliğinin belirtilen sayfa yüksekliğinden değil, içerik boyutundan belirlendiğini belirtir. Bu işaret belirtilirse, tüm belge içeriği tek sayfada yer alacaktır. |
| ScaleToPageWidth | `100` | Bu bayrak, belge içeriğinin, kullanılabilir sayfa genişliği ile örtüşen içerik arasındaki farkın en büyük olduğu sayfaya sığacak şekilde ölçekleneceğini belirtir. ile çakışıyorFitToContentWidth bayrağı ve her iki bayrak da yalnızca belirtilmişseScaleToPageWidth etkilenecek. |
| ScaleToPageHeight | `1000` | Bu bayrak, belge içeriğinin ilk sayfanın yüksekliğine sığacak şekilde ölçekleneceğini belirtir. ile çakışıyorFitToContentHeight bayrağı ve her iki bayrak da yalnızca belirtilmişseScaleToPageHeight etkilenecektir. Tüm belge içeriği yalnızca tek sayfaya yerleştirilecektir. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Rendering](../../aspose.html.rendering/)
* toplantı [Aspose.HTML](../../)


