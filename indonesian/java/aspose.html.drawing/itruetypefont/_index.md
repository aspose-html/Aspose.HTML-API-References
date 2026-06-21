---
title: "Antarmuka ITrueTypeFont"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.drawing.ITrueTypeFont. Menyatakan metode untuk bekerja dengan font TrueType."
type: docs

url: /id/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Menyatakan metode untuk bekerja dengan font TrueType.

```java
public interface ITrueTypeFont
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Mengembalikan ukuran data font dalam byte |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Dapatkan nama keluarga font. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Ini harus merupakan kombinasi dari "FamilyName" dan "SubFamilyName". Pengecualian: jika font adalah "Regular" seperti yang ditunjukkan dalam "SubFamilyName", maka gunakan hanya nama keluarga yang terdapat dalam "FamilyName". Pengecualian terhadap definisi nama font lengkap di atas berlaku untuk String platform Microsoft untuk font CFF OpenType: dalam kasus ini, String nama font lengkap harus identik dengan FontName PostScript dalam CFF Name INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Nama Subfamily Font membedakan font dalam grup dengan nama Font Family yang sama. Ini diasumsikan untuk menunjukkan gaya (italic, oblique) dan bobot (light, bold, black, dll.). Font yang tidak memiliki perbedaan khusus dalam bobot atau gaya (misalnya bobot sedang, tidak italic dan bit fsSelection 6 diset) harus memiliki String "Regular" disimpan pada posisi ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Mengembalikan ascent, dalam poin. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Buka aliran dengan data font. Pemanggil bertanggung jawab untuk membuang aliran. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Mengembalikan descent, dalam poin. |

### Lihat Juga

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
