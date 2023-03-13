---
title: Interface IBlob
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.IO.IBlob arayüz. Bir Blob nesnesi bir bayt dizisine atıfta bulunur ve bayt dizisindeki toplam bayt sayısı olan bir boyut özniteliğine ve bayt dizisinin ortam türünü temsil eden küçük harflerle ASCII kodlu bir dize olan bir tür özniteliğine sahiptir. .
type: docs
weight: 3700
url: /tr/net/aspose.html.io/iblob/
---
## IBlob interface

Bir Blob nesnesi, bir bayt dizisine atıfta bulunur ve bayt dizisindeki toplam bayt sayısı olan bir boyut özniteliğine ve bayt dizisinin ortam türünü temsil eden küçük harflerle ASCII kodlu bir dize olan bir tür özniteliğine sahiptir. .

```csharp
public interface IBlob
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | Bayt dizisinin boyutunu bayt sayısı olarak döndürür. Alma sırasında, uygun kullanıcı aracıları, bir FileReader veya FileReaderSync nesnesi tarafından okunabilen toplam bayt sayısını veya Blob'da okunacak bayt yoksa 0 döndürmelidir. . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | Blob'un ortam türünü temsil eden küçük harfli ASCII kodlu dize. Alınırken, kullanıcı aracıları Blob türünü küçük harfli ASCII kodlu dize olarak döndürmelidir, öyle ki bir bayta dönüştürüldüğünde dizi, ayrıştırılabilir bir MIME türüdür, veya tür belirlenemezse boş dize – 0 bayt – olur. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | İsteğe bağlı başlangıç parametresinden isteğe bağlı bitiş parametresi 'ye kadar olan ancak bu parametreyi içermeyen baytlara ve isteğe bağlı contentType parametresinin değeri olan bir type özniteliğine sahip yeni bir Blob nesnesi döndürür. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.IO](../../aspose.html.io/)
* toplantı [Aspose.HTML](../../)


