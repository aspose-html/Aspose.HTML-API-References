---
title: Enum PageLayoutOptions
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Rendering.PageLayoutOptions enum. Menentukan flag yang bersama dengan opsi PageSetup lainnya menentukan ukuran dan tata letak halaman. Flag ini dapat digabungkan bersama sesuai dengan deskripsinya.
type: docs
weight: 4380
url: /id/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Menentukan flag yang bersama dengan opsi PageSetup lainnya menentukan ukuran dan tata letak halaman. Flag ini dapat digabungkan bersama sesuai dengan deskripsinya.

```csharp
[Flags]
public enum PageLayoutOptions
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| None | `0` | Nilai default yang menunjukkan bahwa PageLayoutOptions tidak akan memengaruhi ukuran dan tata letak halaman. |
| FitToContentWidth | `1` | Bendera ini menunjukkan bahwa lebar halaman ditentukan dari ukuran konten itu sendiri, bukan dari lebar halaman yang ditentukan. Lebar konten dihitung secara individual untuk setiap halaman. |
| UseWidestPage | `2` | Bila digabungkan denganFitToContentWidth menunjukkan bahwa lebar setiap halaman akan sama dan akan sama dengan ukuran konten terluas di antara semua halaman. |
| FitToWidestContentWidth | `3` | Bendera ini menunjukkan bahwa lebar halaman ditentukan dari ukuran konten itu sendiri, bukan dari lebar halaman yang ditentukan. Lebar setiap halaman akan sama dan akan sama dengan ukuran konten terluas di antara semua halaman. |
| FitToContentHeight | `10` | Bendera ini menunjukkan bahwa tinggi halaman ditentukan dari ukuran konten itu sendiri, bukan dari tinggi halaman yang ditentukan. Semua konten dokumen akan ditempatkan pada satu halaman jika bendera ini ditentukan. |
| ScaleToPageWidth | `100` | Bendera ini menunjukkan bahwa konten dokumen akan diskalakan agar pas dengan halaman di mana perbedaan antara lebar halaman yang tersedia dan konten yang tumpang tindih paling besar. Berbenturan denganFitToContentWidth flag dan jika kedua flag hanya ditentukanScaleToPageWidth akan berpengaruh. |
| ScaleToPageHeight | `1000` | Bendera ini menunjukkan bahwa konten dokumen akan diskalakan agar sesuai dengan tinggi halaman pertama. Tabrakan denganFitToContentHeight flag dan jika kedua flag hanya ditentukanScaleToPageHeight akan berpengaruh. Semua konten dokumen akan ditempatkan pada satu halaman saja. |

### Lihat juga

* ruang nama [Aspose.Html.Rendering](../../aspose.html.rendering/)
* perakitan [Aspose.HTML](../../)


