---
title: FontMatcher.MatchFontFallback
second_title: Aspose.HTML untuk Referensi .NET API
description: FontMatcher metode. Metode ini dipanggil jika tidak ada font yang sesuai ditemukan di folder pencarian font. Metode ini akan mengembalikan font tipe sebenarnya berdasarkanfontMatchingProperties yang dapat merendercharCode  ataubatal jika font tersebut tidak tersedia.
type: docs
weight: 10
url: /id/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Metode ini dipanggil jika tidak ada font yang sesuai ditemukan di folder pencarian font. Metode ini akan mengembalikan font tipe sebenarnya berdasarkan*fontMatchingProperties* yang dapat merender*charCode* , atau`batal` jika font tersebut tidak tersedia.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Properti font yang cocok. |
| charCode | UInt32 | Kode karakter yang akan dirender menggunakan font yang cocok. |

### Nilai Pengembalian

Array byte yang berisi data font atau`batal`.

### Lihat juga

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* ruang nama [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* perakitan [Aspose.HTML](../../../)


