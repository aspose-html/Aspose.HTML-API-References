---
title: Class OutputStream
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.IO.OutputStream sınıf. Yedek akış gerçek çıkış akışını sarar ve ona erişimi kontrol eder. OutputStream çıkış akışının konumunu açıklayan URI verilerini içerir.
type: docs
weight: 3750
url: /tr/net/aspose.html.io/outputstream/
---
## OutputStream class

Yedek akış, gerçek çıkış akışını sarar ve ona erişimi kontrol eder. `OutputStream` çıkış akışının konumunu açıklayan URI verilerini içerir.

```csharp
public class OutputStream : Stream
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | Yeni bir örneğini başlatır.`OutputStream` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | Sarılmış çıktı akışının okumayı destekleyip desteklemediğini gösteren bir değer alır. |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | Sarılmış çıktı akışının aramayı destekleyip desteklemediğini gösteren bir değer alır. |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | Sarılmış çıktı akışının yazmayı destekleyip desteklemediğini gösteren bir değer alır. |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | Sarılmış çıktı akışının bayt cinsinden uzunluğunu alır. |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | Sarılmış çıktı akışı içindeki konumu alır veya ayarlar. |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | Akış konumunun URI'sini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | Sarılmış çıktı akışını ve geçerli akışı kapatır. |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | Sarılmış çıktı akışı için tüm arabellekleri temizler ve arabelleğe alınan tüm verilerin alttaki aygıta yazılmasına neden olur. |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | Sarılmış çıktı akışından bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | Sarılmış çıktı akışı içindeki konumu ayarlar. |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | Sarılmış çıktı akışının uzunluğunu ayarlar. |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | Sarılmış output akışına bir bayt dizisi yazar ve bu akış içindeki mevcut konumu yazılan bayt sayısı kadar ilerletir. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.IO](../../aspose.html.io/)
* toplantı [Aspose.HTML](../../)


