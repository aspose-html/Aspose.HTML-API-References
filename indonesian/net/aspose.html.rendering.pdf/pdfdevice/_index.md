---
title: Class PdfDevice
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Rendering.Pdf.PdfDevice kelas. Mewakili rendering ke dokumen pdf.
type: docs
weight: 4440
url: /id/net/aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Mewakili rendering ke dokumen pdf.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Menginisialisasi instance baru dari`PdfDevice` kelas. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Menginisialisasi instance baru dari`PdfDevice` kelas. |
| [PdfDevice](pdfdevice/#constructor_5)(string) | Menginisialisasi instance baru dari`PdfDevice` kelas. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Menginisialisasi instance baru dari`PdfDevice` kelas dengan merender opsi dan penyedia streaming. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Menginisialisasi instance baru dari`PdfDevice`kelas dengan merender opsi dan aliran keluaran. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, string) | Menginisialisasi instance baru dari`PdfDevice` kelas dengan merender opsi dan nama file keluaran. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.pdf/pdfdevice/addrect/)(RectangleF) | Menambahkan persegi panjang ke jalur saat ini sebagai subjalur lengkap. |
| override [BeginDocument](../../aspose.html.rendering.pdf/pdfdevice/begindocument/)(Document) | Memulai rendering dokumen. |
| override [BeginElement](../../aspose.html.rendering.pdf/pdfdevice/beginelement/)(Element, RectangleF) | Memulai rendering elemen. |
| override [BeginPage](../../aspose.html.rendering.pdf/pdfdevice/beginpage/)(SizeF) | Memulai rendering halaman baru. |
| override [Clip](../../aspose.html.rendering.pdf/pdfdevice/clip/)(FillMode) | Memodifikasi jalur kliping saat ini dengan memotongnya dengan jalur saat ini, menggunakan aturan FillMode untuk menentukan wilayah yang akan diisi. Metode ini menghentikan jalur saat ini. |
| override [ClosePath](../../aspose.html.rendering.pdf/pdfdevice/closepath/)() | Menutup subjalur saat ini dengan menambahkan segmen garis lurus dari titik saat ini ke titik awal subjalur. Jika subjalur saat ini sudah ditutup, "ClosePath" tidak melakukan apa pun. Operator ini menghentikan subjalur saat ini. Menambahkan segmen lain ke jalur saat ini memulai subjalur baru, bahkan jika segmen baru dimulai pada titik akhir yang dijangkau oleh metode "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.pdf/pdfdevice/cubicbezierto/)(PointF, PointF, PointF) | Menambahkan kurva Bézier kubik ke jalur saat ini. Kurva memanjang dari titik saat ini ke titik pt2, menggunakan pt1 dan pt2 sebagai titik kontrol Bézier. Titik baru saat ini adalah pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.pdf/pdfdevice/drawimage/)(byte[], ImageType, RectangleF) | Menggambar gambar yang ditentukan. |
| override [EndDocument](../../aspose.html.rendering.pdf/pdfdevice/enddocument/)() | Mengakhiri rendering dokumen. |
| override [EndElement](../../aspose.html.rendering.pdf/pdfdevice/endelement/)(Element) | Mengakhiri rendering elemen. |
| override [EndPage](../../aspose.html.rendering.pdf/pdfdevice/endpage/)() | Mengakhiri rendering halaman saat ini. |
| override [Fill](../../aspose.html.rendering.pdf/pdfdevice/fill/)(FillMode) | Mengisi seluruh wilayah yang dilingkupi oleh jalur saat ini. Jika jalur terdiri dari beberapa subjalur yang terputus, jalur tersebut mengisi bagian dalam semua subjalur, dipertimbangkan bersama. Metode ini menghentikan jalur saat ini. |
| override [FillText](../../aspose.html.rendering.pdf/pdfdevice/filltext/)(string, PointF) | Mengisi string teks yang ditentukan di lokasi yang ditentukan. |
| override [Flush](../../aspose.html.rendering.pdf/pdfdevice/flush/)() | Membuang semua data ke aliran keluaran. |
| override [LineTo](../../aspose.html.rendering.pdf/pdfdevice/lineto/)(PointF) | Menambahkan segmen garis lurus dari titik saat ini ke titik (pt). Titik baru saat ini adalah pt. |
| override [MoveTo](../../aspose.html.rendering.pdf/pdfdevice/moveto/)(PointF) | Memulai subjalur baru dengan memindahkan titik saat ini ke koordinat parameter pt, menghilangkan segmen garis penghubung apa pun. Jika metode pembuatan jalur sebelumnya di jalur saat ini juga "MoveTo", "MoveTo" baru akan menimpanya; tidak ada sisa dari operasi "MoveTo" sebelumnya yang tersisa di jalur. |
| override [RestoreGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/restoregraphiccontext/)() | Mengembalikan seluruh konteks grafik ke nilai sebelumnya dengan mengeluarkannya dari tumpukan. |
| override [SaveGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/savegraphiccontext/)() | Mendorong salinan seluruh konteks grafik ke tumpukan. |
| override [Stroke](../../aspose.html.rendering.pdf/pdfdevice/stroke/)() | Memotong garis di sepanjang jalur saat ini. Garis yang digores mengikuti setiap segmen lurus atau melengkung di jalur, berpusat pada segmen dengan sisi sejajar dengannya. Setiap subjalur jalur diperlakukan secara terpisah. Metode ini menghentikan jalur saat ini. |
| override [StrokeAndFill](../../aspose.html.rendering.pdf/pdfdevice/strokeandfill/)(FillMode) | Goresan dan isi jalur saat ini. Metode ini mengakhiri jalur saat ini. |
| override [StrokeText](../../aspose.html.rendering.pdf/pdfdevice/stroketext/)(string, PointF) | Memotong string teks yang ditentukan di lokasi yang ditentukan. |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [PdfGraphicContext](pdfdevice.pdfgraphiccontext/) | Menyimpan parameter kontrol grafis saat ini untuk PdfDevice. Parameter ini menentukan kerangka kerja global tempat operator grafis mengeksekusi. |

### Lihat juga

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* ruang nama [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* perakitan [Aspose.HTML](../../)


