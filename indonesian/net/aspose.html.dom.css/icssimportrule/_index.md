---
title: Interface ICSSImportRule
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Css.ICSSImportRule antarmuka. Antarmuka CSSImportRule mewakili aturan import dalam lembar gaya CSS. Aturan import digunakan untuk mengimpor aturan gaya dari lembar gaya lain.
type: docs
weight: 410
url: /id/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

Antarmuka CSSImportRule mewakili aturan @import dalam lembar gaya CSS. Aturan @import digunakan untuk mengimpor aturan gaya dari lembar gaya lain.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | Lokasi style sheet yang akan diimpor. Atribut tidak akan berisi penentu "url(...)" di sekitar URI. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | Daftar jenis media yang mungkin menggunakan style sheet ini. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | Style sheet yang dirujuk oleh aturan ini, jika telah dimuat. Nilai atribut ini adalah null jika style sheet belum dimuat atau jika tidak akan dimuat (misalnya jika style sheet adalah untuk jenis media yang tidak didukung oleh agen pengguna). |

### Lihat juga

* interface [ICSSRule](../icssrule/)
* ruang nama [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* perakitan [Aspose.HTML](../../)


