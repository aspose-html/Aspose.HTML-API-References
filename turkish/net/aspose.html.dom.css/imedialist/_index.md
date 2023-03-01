---
title: Interface IMediaList
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Css.IMediaList arayüz. MediaList arayüzü bu koleksiyonun nasıl uygulanacağını tanımlamadan veya kısıtlamadan sıralı bir medya koleksiyonunun soyutlanmasını sağlar. Boş bir liste all ortamını içeren listeyle aynıdır.
type: docs
weight: 580
url: /tr/net/aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList arayüzü, bu koleksiyonun nasıl uygulanacağını tanımlamadan veya kısıtlamadan, sıralı bir medya koleksiyonunun soyutlanmasını sağlar. Boş bir liste, "all" ortamını içeren listeyle aynıdır.

```csharp
public interface IMediaList : IEnumerable<string>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Item](../../aspose.html.dom.css/imedialist/item/) { get; } | Listedeki indeksi döndürür. Dizin, listedeki ortam sayısından büyük veya ona eşitse, bu, null. değerini döndürür.Medya dizini. |
| [Length](../../aspose.html.dom.css/imedialist/length/) { get; } | Listedeki ortam sayısı. Geçerli ortam aralığı, 0 ila uzunluk-1'dir. |
| [MediaText](../../aspose.html.dom.css/imedialist/mediatext/) { get; } | Ortam listesinin ayrıştırılabilir metinsel gösterimi. Bu, virgülle ayrılmış bir ortam listesidir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AppendMedium](../../aspose.html.dom.css/imedialist/appendmedium/)(string) | Listenin sonuna newMedium ortamını ekler. newMedium zaten kullanılıyorsa, önce kaldırılır. |
| [DeleteMedium](../../aspose.html.dom.css/imedialist/deletemedium/)(string) | oldMedium tarafından belirtilen ortamı listeden siler. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* toplantı [Aspose.HTML](../../)


