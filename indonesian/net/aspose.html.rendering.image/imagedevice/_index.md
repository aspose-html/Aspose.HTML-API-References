---
title: Class ImageDevice
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Rendering.Image.ImageDevice kelas. Mewakili rendering ke format raster jpeg png bmp gif tiff.
type: docs
weight: 4300
url: /id/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Mewakili rendering ke format raster: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Menginisialisasi instance baru dari`ImageDevice` kelas. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Menginisialisasi instance baru dari`ImageDevice` kelas. |
| [ImageDevice](imagedevice/#constructor_5)(string) | Menginisialisasi instance baru dari`ImageDevice` kelas. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Menginisialisasi instance baru dari`ImageDevice` kelas dengan merender opsi dan penyedia streaming. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Menginisialisasi instance baru dari`ImageDevice`kelas dengan merender opsi dan aliran keluaran. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | Menginisialisasi instance baru dari`ImageDevice` kelas dengan merender opsi dan nama file keluaran. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Mendapat instance Graphics. |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | Menambahkan persegi panjang ke jalur saat ini sebagai subjalur lengkap. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | Memulai rendering dokumen. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | Memulai rendering elemen. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | Memulai rendering halaman baru. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | Memodifikasi jalur kliping saat ini dengan memotongnya dengan jalur saat ini, menggunakan aturan FillMode untuk menentukan wilayah yang akan diisi. Metode ini menghentikan jalur saat ini. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | Menutup subjalur saat ini dengan menambahkan segmen garis lurus dari titik saat ini ke titik awal subjalur. Jika subjalur saat ini sudah ditutup, "ClosePath" tidak melakukan apa pun. Operator ini menghentikan subjalur saat ini. Menambahkan segmen lain ke jalur saat ini memulai subjalur baru, bahkan jika segmen baru dimulai pada titik akhir yang dijangkau oleh metode "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | Menambahkan kurva Bézier kubik ke jalur saat ini. Kurva memanjang dari titik saat ini ke titik pt2, menggunakan pt1 dan pt2 sebagai titik kontrol Bézier. Titik baru saat ini adalah pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | Menggambar gambar yang ditentukan. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | Mengakhiri rendering dokumen. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | Mengakhiri rendering elemen. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | Mengakhiri rendering halaman saat ini. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | Mengisi seluruh wilayah yang dilingkupi oleh jalur saat ini. Jika jalur terdiri dari beberapa subjalur yang terputus, jalur tersebut mengisi bagian dalam semua subjalur, dipertimbangkan bersama. Metode ini menghentikan jalur saat ini. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | Mengisi string teks yang ditentukan di lokasi yang ditentukan. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | Membuang semua data ke aliran keluaran. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | Menambahkan segmen garis lurus dari titik saat ini ke titik (pt). Titik baru saat ini adalah pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | Memulai subjalur baru dengan memindahkan titik saat ini ke koordinat parameter pt, menghilangkan segmen garis penghubung apa pun. Jika metode pembuatan jalur sebelumnya di jalur saat ini juga "MoveTo", "MoveTo" baru akan menimpanya; tidak ada sisa dari operasi "MoveTo" sebelumnya yang tersisa di jalur. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | Mengembalikan seluruh konteks grafik ke nilai sebelumnya dengan mengeluarkannya dari tumpukan. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | Mendorong salinan seluruh konteks grafik ke tumpukan. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | Memotong garis di sepanjang jalur saat ini. Garis yang digores mengikuti setiap segmen lurus atau melengkung di jalur, berpusat pada segmen dengan sisi sejajar dengannya. Setiap subjalur jalur diperlakukan secara terpisah. Metode ini menghentikan jalur saat ini. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | Goresan dan isi jalur saat ini. Metode ini mengakhiri jalur saat ini. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | Memotong string teks yang ditentukan di lokasi yang ditentukan. |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | Menyimpan parameter kontrol grafik saat ini untuk`ImageDevice` . Parameter ini menentukan kerangka kerja global tempat operator grafis mengeksekusi. |

### Lihat juga

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* ruang nama [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* perakitan [Aspose.HTML](../../)


