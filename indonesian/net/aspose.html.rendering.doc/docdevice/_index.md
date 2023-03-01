---
title: Class DocDevice
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Rendering.Doc.DocDevice kelas. Mewakili rendering ke dokumen DOCX.
type: docs
weight: 4170
url: /id/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Mewakili rendering ke dokumen DOCX.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Menginisialisasi instance baru dari`DocDevice` kelas. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Menginisialisasi instance baru dari`DocDevice` kelas dengan aliran keluaran. |
| [DocDevice](docdevice/#constructor_5)(string) | Menginisialisasi instance baru dari`DocDevice` kelas dengan nama file keluaran. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Menginisialisasi instance baru dari`DocDevice` kelas dengan merender opsi dan penyedia streaming. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Menginisialisasi instance baru dari`DocDevice` kelas dengan merender opsi dan aliran keluaran. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | Menginisialisasi instance baru dari`DocDevice` kelas dengan merender opsi dan nama file keluaran. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Menambahkan persegi panjang ke jalur saat ini sebagai subjalur lengkap. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Memulai rendering dokumen. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Memulai rendering node html. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Memulai rendering halaman baru. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Memodifikasi jalur kliping saat ini dengan memotongnya dengan jalur saat ini, menggunakan aturan FillMode untuk menentukan wilayah yang akan diisi. Metode ini menghentikan jalur saat ini. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | Menutup subjalur saat ini dengan menambahkan segmen garis lurus dari titik saat ini ke titik awal subjalur. Jika subjalur saat ini sudah ditutup, "ClosePath" tidak melakukan apa pun. Operator ini menghentikan subjalur saat ini. Menambahkan segmen lain ke jalur saat ini memulai subjalur baru, bahkan jika segmen baru dimulai pada titik akhir yang dijangkau oleh metode "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Menambahkan kurva Bézier kubik ke jalur saat ini. Kurva memanjang dari titik saat ini ke titik pt2, menggunakan pt1 dan pt2 sebagai titik kontrol Bézier. Titik baru saat ini adalah pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Menggambar gambar yang ditentukan. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | Mengakhiri rendering node html. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | Mengakhiri rendering halaman saat ini. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Mengisi seluruh wilayah yang dilingkupi oleh jalur saat ini. Jika jalur terdiri dari beberapa subjalur yang terputus, jalur tersebut mengisi bagian dalam semua subjalur, dipertimbangkan bersama. Metode ini menghentikan jalur saat ini. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | Mengisi string teks yang ditentukan di lokasi yang ditentukan. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | Membuang semua data ke aliran keluaran. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Menambahkan segmen garis lurus dari titik saat ini ke titik (pt). Titik baru saat ini adalah pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Memulai subjalur baru dengan memindahkan titik saat ini ke koordinat parameter pt, menghilangkan segmen garis penghubung apa pun. Jika metode pembuatan jalur sebelumnya di jalur saat ini juga "MoveTo", "MoveTo" baru akan menimpanya; tidak ada sisa dari operasi "MoveTo" sebelumnya yang tersisa di jalur. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Mengembalikan seluruh konteks grafik ke nilai sebelumnya dengan mengeluarkannya dari tumpukan. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Mendorong salinan seluruh konteks grafik ke tumpukan. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | Memotong garis di sepanjang jalur saat ini. Garis yang digores mengikuti setiap segmen lurus atau melengkung di jalur, berpusat pada segmen dengan sisi sejajar dengannya. Setiap subjalur jalur diperlakukan secara terpisah. Metode ini menghentikan jalur saat ini. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Goresan dan isi jalur saat ini. Metode ini mengakhiri jalur saat ini. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | Memotong string teks yang ditentukan di lokasi yang ditentukan. |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | Menyimpan parameter kontrol grafis saat ini untuk DocDevice. Parameter ini menentukan kerangka kerja global tempat operator grafis mengeksekusi. |

### Lihat juga

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* ruang nama [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* perakitan [Aspose.HTML](../../)


