---
title: "Enum PdfPermissions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "enum com.aspose.html.rendering.pdf.encryption.PdfPermissions. Enum ini mewakili izin pengguna untuk sebuah pdf"
type: docs

url: /id/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Enum ini mewakili izin pengguna untuk pdf.

```java
[Flags]
public enum PdfPermissions
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| PrintDocument | `4` | (Penangani keamanan revisi 2) Mencetak dokumen. (Penangani keamanan revisi 3 atau lebih) Mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah PrintingQuality juga diatur). |
| ModifyContent | `8` | Memodifikasi isi dokumen dengan operasi selain yang dikendalikan oleh ModifyTextAnnotations, FillForm, dan 11. |
| ExtractContent | `10` | (Penangani keamanan revisi 2) Menyalin atau mengekstrak teks dan grafik dari dokumen, termasuk mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau tujuan lain). (Penangani keamanan revisi 3 atau lebih) Menyalin atau mengekstrak teks dan grafik dari dokumen dengan operasi selain yang dikendalikan oleh ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Menambahkan atau memodifikasi anotasi teks, mengisi bidang formulir interaktif, dan, jika ModifyContent juga diatur, membuat atau memodifikasi bidang formulir interaktif (termasuk bidang tanda tangan). |
| FillForm | `100` | (Penangani keamanan revisi 3 atau lebih) Mengisi bidang formulir interaktif yang ada (termasuk bidang tanda tangan), bahkan jika ModifyTextAnnotations tidak diatur. |
| ExtractContentWithDisabilities | `200` | (Penangani keamanan revisi 3 atau lebih) Mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau tujuan lain). |
| AssembleDocument | `400` | (Penangani keamanan revisi 3 atau lebih) Menyusun dokumen (menyisipkan, memutar, atau menghapus halaman serta membuat bookmark atau gambar mini), bahkan jika ModifyContent tidak diatur. |
| PrintingQuality | `800` | (Penangani keamanan revisi 3 atau lebih) Mencetak dokumen ke representasi yang dapat menghasilkan salinan digital yang setia dari konten PDF. Ketika bit ini tidak diatur (dan bit 3 diatur), pencetakan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang menurun. |

### Lihat Juga

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
