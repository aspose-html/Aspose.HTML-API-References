---
title: Interface ICSSStyleSheet
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Css.ICSSStyleSheet antarmuka. Antarmuka CSSStyleSheet adalah antarmuka konkret yang digunakan untuk mewakili lembar gaya CSS yaitu lembar gaya yang jenis kontennya adalah teks/css.
type: docs
weight: 510
url: /id/net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Antarmuka CSSStyleSheet adalah antarmuka konkret yang digunakan untuk mewakili lembar gaya CSS yaitu, lembar gaya yang jenis kontennya adalah "teks/css".

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules/) { get; } | Daftar semua aturan CSS yang ada di dalam style sheet. Ini termasuk kumpulan aturan dan at-rules. |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule/) { get; } | Jika style sheet ini berasal dari aturan @import, atribut ownerRule akan berisi CSSImportRule. Dalam hal ini, atribut ownerNode di antarmuka StyleSheet akan menjadi nol. Jika style sheet berasal dari elemen atau instruksi pemrosesan, atribut ownerRule akan menjadi null dan atribut ownerNode akan berisi Node. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Digunakan untuk menghapus aturan dari style sheet. |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule/)(string, int) | Digunakan untuk menyisipkan aturan baru ke dalam style sheet. Aturan baru sekarang menjadi bagian dari kaskade. |

### Lihat juga

* interface [IStyleSheet](../istylesheet/)
* ruang nama [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* perakitan [Aspose.HTML](../../)


