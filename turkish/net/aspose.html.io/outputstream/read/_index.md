---
title: OutputStream.Read
second_title: Aspose.HTML for .NET API Referansı
description: OutputStream yöntem. Sarılmış çıktı akışından bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir.
type: docs
weight: 100
url: /tr/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

Sarılmış çıktı akışından bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| buffer | Byte[] | Bir bayt dizisi. Bu yöntem geri döndüğünde, tampon belirtilen bayt dizisini içerir ve ofset ile (kaydırma + sayım - 1) arasındaki değerler, sarılmış çıktı akışından okunan baytlar ile değiştirilir. |
| offset | Int32 | Sarılmış çıktı akışından read verilerinin depolanmaya başlanacağı arabellekteki sıfır tabanlı bayt ofseti. |
| count | Int32 | Sarılmış çıktı akışından okunacak maksimum bayt sayısı. |

### Geri dönüş değeri

Ara belleğe okunan toplam bayt sayısı. Bu, şu anda bu kadar bayt mevcut değilse, istenen byte sayısından daha az olabilir veya akışın sonuna ulaşıldıysa sıfır (0) olabilir.

### Ayrıca bakınız

* class [OutputStream](../)
* ad alanı [Aspose.Html.IO](../../outputstream/)
* toplantı [Aspose.HTML](../../../)


