---
title: Interface ITrueTypeFont
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Drawing.ITrueTypeFont antarmuka. Mendeklarasikan metode untuk bekerja dengan font TrueType.
type: docs
weight: 2760
url: /id/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Mendeklarasikan metode untuk bekerja dengan font TrueType.

```csharp
public interface ITrueTypeFont
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | Mengembalikan ukuran data font dalam byte |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | Dapatkan nama font family. |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | Ini harus merupakan kombinasi dari "FamilyName" dan "SubFamilyName". Pengecualian: jika fontnya "Regular" seperti yang ditunjukkan di "SubFamilyName", maka gunakan hanya nama keluarga yang terdapat di "FamilyName". Pengecualian untuk definisi Nama font lengkap di atas adalah untuk string platform Microsoft untuk font OpenType CFF: dalam hal ini, string Nama font lengkap harus identik dengan PostScript FontName di CFF Name INDEX. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | Nama Subfamili Font membedakan font dalam grup dengan nama Font Family yang sama. Ini diasumsikan untuk mengatasi gaya (miring, miring) dan berat (ringan, tebal, hitam, dll.). Sebuah font tanpa perbedaan tertentu dalam berat atau gaya (misalnya berat sedang, tidak italic dan set fsSelection bit 6) harus memiliki string "Regular" yang disimpan di posisi ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | Mengembalikan pendakian, dalam poin. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | Buka aliran dengan data font. Penelepon bertanggung jawab untuk membuang aliran. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | Mengembalikan turunan, dalam poin. |

### Lihat juga

* ruang nama [Aspose.Html.Drawing](../../aspose.html.drawing/)
* perakitan [Aspose.HTML](../../)


