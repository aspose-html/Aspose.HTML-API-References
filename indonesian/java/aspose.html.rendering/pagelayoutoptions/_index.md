---
title: "Enum PageLayoutOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "enum com.aspose.html.rendering.PageLayoutOptions. Menentukan flag yang bersama dengan opsi PageSetup lainnya menentukan ukuran dan tata letak halaman. Flag ini dapat digabungkan bersama sesuai dengan deskripsinya."
type: docs

url: /id/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Menentukan flag yang bersama dengan opsi PageSetup lainnya menentukan ukuran dan tata letak halaman. Flag ini dapat digabungkan sesuai dengan deskripsinya.

```java
[Flags]
public enum PageLayoutOptions
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Nilai default yang menunjukkan bahwa PageLayoutOptions tidak akan memengaruhi ukuran dan tata letak halaman. |
| FitToContentWidth | `1` | Flag ini menunjukkan bahwa lebar halaman ditentukan dari ukuran konten itu sendiri, bukan dari lebar halaman yang ditentukan. Lebar konten dihitung secara individual untuk setiap halaman. |
| UseWidestPage | `2` | Ketika digabungkan dengan FitToContentWidth, menunjukkan bahwa lebar setiap halaman akan sama dan akan sama dengan ukuran konten terlebar di antara semua halaman. |
| FitToWidestContentWidth | `3` | Flag ini menunjukkan bahwa lebar halaman ditentukan dari ukuran konten itu sendiri, bukan dari lebar halaman yang ditentukan. Lebar setiap halaman akan sama dan akan sama dengan ukuran konten terlebar di antara semua halaman. |
| FitToContentHeight | `10` | Flag ini menunjukkan bahwa tinggi halaman ditentukan dari ukuran konten itu sendiri, bukan dari tinggi halaman yang ditentukan. Semua konten dokumen akan ditempatkan pada satu halaman jika flag ini ditentukan. |
| ScaleToPageWidth | `100` | Flag ini menunjukkan bahwa konten dokumen akan diskalakan agar sesuai dengan halaman di mana selisih antara lebar halaman yang tersedia dan konten yang tumpang tindih paling besar. Flag ini bertentangan dengan FitToContentWidth dan jika kedua flag ditentukan, hanya ScaleToPageWidth yang akan berpengaruh. |
| ScaleToPageHeight | `1000` | Flag ini menunjukkan bahwa konten dokumen akan diskalakan agar sesuai dengan tinggi halaman pertama. Flag ini bertentangan dengan FitToContentHeight dan jika kedua flag ditentukan, hanya ScaleToPageHeight yang akan berpengaruh. Semua konten dokumen akan ditempatkan hanya pada satu halaman. |

### Lihat Juga

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
