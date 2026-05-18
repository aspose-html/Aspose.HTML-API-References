---
title: "FontMatcher.MatchFontFallback"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode FontMatcher. Metode ini dipanggil jika tidak ada font yang sesuai ditemukan di folder pencarian font. Metode ini harus mengembalikan true type font berdasarkan fontMatchingProperties yang dapat merender charCode atau null jika font tersebut tidak tersedia"
type: docs

url: /id/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Metode ini dipanggil jika tidak ada font yang sesuai ditemukan di folder pencarian font. Metode ini harus mengembalikan font TrueType berdasarkan *fontMatchingProperties* yang dapat merender *charCode*, atau `null` jika font tersebut tidak tersedia.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Properti dari font yang cocok. |
| charCode | UInt32 | Kode karakter yang akan dirender menggunakan font yang cocok. |

### Nilai Kembali

Array byte yang berisi data font atau `null`.

### Lihat Juga

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
