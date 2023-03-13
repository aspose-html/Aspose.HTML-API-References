---
title: Enum PdfPermissions
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions enum. Enum ini mewakili izin pengguna untuk pdf.
type: docs
weight: 4420
url: /id/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Enum ini mewakili izin pengguna untuk pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| PrintDocument | `4` | (Penangan keamanan revisi 2) Cetak dokumen. (Pengendali keamanan revisi 3 atau lebih tinggi) Mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah PrintingQuality juga diatur). |
| ModifyContent | `8` | Memodifikasi konten dokumen dengan operasi selain yang dikontrol oleh ModifyTextAnnotations, FillForm, dan 11. |
| ExtractContent | `10` | Penangan keamanan revisi 2) Salin atau ekstrak teks dan grafik dari dokumen, termasuk mengekstraksi teks dan grafik (untuk mendukung aksesibilitas bagi pengguna penyandang cacat atau untuk tujuan lain). (Penangan keamanan revisi 3 atau lebih) Salin atau mengekstrak teks dan grafik dari dokumen dengan operasi selain yang dikontrol oleh ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Tambahkan atau ubah anotasi teks, isi bidang formulir interaktif, dan, jika ModifyContent juga disetel, buat atau ubah bidang formulir interaktif (termasuk bidang tanda tangan). |
| FillForm | `100` | (Penangan keamanan revisi 3 atau lebih) Isi bidang formulir interaktif yang ada (termasuk bidang tanda tangan), bahkan jika ModifyTextAnnotations jelas. |
| ExtractContentWithDisabilities | `200` | (Penangan keamanan revisi 3 atau lebih tinggi) Mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna penyandang cacat atau untuk tujuan lain). |
| AssembleDocument | `400` | (Penangan keamanan revisi 3 atau lebih) Merakit dokumen (memasukkan, memutar, atau menghapus halaman dan membuat bookmark atau gambar kecil), bahkan jika ModifyContent jelas. |
| PrintingQuality | `800` | (Pengendali keamanan revisi 3 atau lebih tinggi) Mencetak dokumen ke representasi dari mana salinan digital setia konten PDF dapat dibuat. Ketika bit ini jelas (dan bit 3 disetel), pencetakan dibatasi hingga rendah -representasi tingkat penampilan, mungkin kualitasnya menurun. |

### Lihat juga

* ruang nama [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* perakitan [Aspose.HTML](../../)


