---
title: Interface IStyleSheet
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Css.IStyleSheet antarmuka. Antarmuka StyleSheet adalah antarmuka dasar abstrak untuk semua jenis style sheet. Ini mewakili satu lembar gaya yang terkait dengan dokumen terstruktur.
type: docs
weight: 590
url: /id/net/aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

Antarmuka StyleSheet adalah antarmuka dasar abstrak untuk semua jenis style sheet. Ini mewakili satu lembar gaya yang terkait dengan dokumen terstruktur.

```csharp
public interface IStyleSheet
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Disabled](../../aspose.html.dom.css/istylesheet/disabled/) { get; set; } | false jika style sheet diterapkan ke dokumen. benar jika tidak. Memodifikasi atribut ini dapat menyebabkan resolusi gaya baru untuk dokumen. Lembar gaya hanya berlaku jika ada definisi media yang sesuai dan atribut yang dinonaktifkan salah. Jadi, jika media tidak berlaku untuk agen pengguna saat ini, atribut dinonaktifkan akan diabaikan. |
| [Href](../../aspose.html.dom.css/istylesheet/href/) { get; } | Jika style sheet adalah style sheet tertaut, nilai atributnya adalah lokasinya. Untuk lembar gaya sebaris, nilai atribut ini adalah nol. |
| [Media](../../aspose.html.dom.css/istylesheet/media/) { get; } | Media tujuan yang dimaksud untuk informasi gaya. |
| [OwnerNode](../../aspose.html.dom.css/istylesheet/ownernode/) { get; } | Node yang menghubungkan style sheet ini dengan dokumen. Untuk HTML, ini mungkin elemen LINK atau GAYA yang sesuai. Untuk XML, ini mungkin merupakan instruksi pemrosesan penautan. Untuk style sheet yang disertakan oleh style sheet lain, nilai atribut ini adalah null. |
| [ParentStyleSheet](../../aspose.html.dom.css/istylesheet/parentstylesheet/) { get; } | Untuk bahasa style sheet yang mendukung konsep penyertaan style sheet, atribut ini mewakili style sheet yang disertakan, jika ada. Jika style sheet adalah style sheet tingkat atas, atau bahasa style sheet tidak mendukung penyertaan, nilai atribut ini adalah null. |
| [Title](../../aspose.html.dom.css/istylesheet/title/) { get; } | Judul penasehat. |
| [Type](../../aspose.html.dom.css/istylesheet/type/) { get; } | Ini menentukan bahasa style sheet untuk style sheet ini. Bahasa style sheet ditetapkan sebagai tipe konten (misalnya "text/css"). |

### Lihat juga

* ruang nama [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* perakitan [Aspose.HTML](../../)


