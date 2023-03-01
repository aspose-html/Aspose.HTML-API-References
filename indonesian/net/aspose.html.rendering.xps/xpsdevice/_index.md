---
title: Class XpsDevice
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Rendering.Xps.XpsDevice kelas. Mewakili rendering ke dokumen xps.
type: docs
weight: 4530
url: /id/net/aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Mewakili rendering ke dokumen xps.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Menginisialisasi instance baru dari`XpsDevice` kelas. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Menginisialisasi instance baru dari`XpsDevice` kelas. |
| [XpsDevice](xpsdevice/#constructor_5)(string) | Menginisialisasi instance baru dari`XpsDevice` kelas. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Menginisialisasi instance baru dari`XpsDevice` kelas dengan merender opsi dan penyedia streaming. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Menginisialisasi instance baru dari`XpsDevice`kelas dengan merender opsi dan aliran keluaran. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, string) | Menginisialisasi instance baru dari`XpsDevice` kelas dengan merender opsi dan nama file keluaran. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.xps/xpsdevice/addrect/)(RectangleF) | Menambahkan persegi panjang ke jalur saat ini sebagai subjalur lengkap. |
| override [BeginDocument](../../aspose.html.rendering.xps/xpsdevice/begindocument/)(Document) | Memulai rendering dokumen. |
| override [BeginElement](../../aspose.html.rendering.xps/xpsdevice/beginelement/)(Element, RectangleF) | Memulai rendering elemen. |
| override [BeginPage](../../aspose.html.rendering.xps/xpsdevice/beginpage/)(SizeF) | Memulai rendering halaman baru. |
| override [Clip](../../aspose.html.rendering.xps/xpsdevice/clip/)(FillMode) | Memodifikasi jalur kliping saat ini dengan memotongnya dengan jalur saat ini, menggunakan aturan FillMode untuk menentukan wilayah yang akan diisi. Metode ini menghentikan jalur saat ini. |
| override [ClosePath](../../aspose.html.rendering.xps/xpsdevice/closepath/)() | Menutup subjalur saat ini dengan menambahkan segmen garis lurus dari titik saat ini ke titik awal subjalur. Jika subjalur saat ini sudah ditutup, "ClosePath" tidak melakukan apa pun. Operator ini menghentikan subjalur saat ini. Menambahkan segmen lain ke jalur saat ini memulai subjalur baru, bahkan jika segmen baru dimulai pada titik akhir yang dijangkau oleh metode "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.xps/xpsdevice/cubicbezierto/)(PointF, PointF, PointF) | Menambahkan kurva Bézier kubik ke jalur saat ini. Kurva memanjang dari titik saat ini ke titik pt2, menggunakan pt1 dan pt2 sebagai titik kontrol Bézier. Titik baru saat ini adalah pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.xps/xpsdevice/drawimage/)(byte[], ImageType, RectangleF) | Menggambar gambar yang ditentukan. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.xps/xpsdevice/endelement/)(Element) | Mengakhiri rendering elemen. |
| override [EndPage](../../aspose.html.rendering.xps/xpsdevice/endpage/)() | Mengakhiri rendering halaman saat ini. |
| override [Fill](../../aspose.html.rendering.xps/xpsdevice/fill/)(FillMode) | Mengisi seluruh wilayah yang dilingkupi oleh jalur saat ini. Jika jalur terdiri dari beberapa subjalur yang terputus, jalur tersebut mengisi bagian dalam semua subjalur, dipertimbangkan bersama. Metode ini menghentikan jalur saat ini. |
| override [FillText](../../aspose.html.rendering.xps/xpsdevice/filltext/)(string, PointF) | Mengisi string teks yang ditentukan di lokasi yang ditentukan. |
| override [Flush](../../aspose.html.rendering.xps/xpsdevice/flush/)() | Membuang semua data ke aliran keluaran. |
| override [LineTo](../../aspose.html.rendering.xps/xpsdevice/lineto/)(PointF) | Menambahkan segmen garis lurus dari titik saat ini ke titik (pt). Titik baru saat ini adalah pt. |
| override [MoveTo](../../aspose.html.rendering.xps/xpsdevice/moveto/)(PointF) | Memulai subjalur baru dengan memindahkan titik saat ini ke koordinat parameter pt, menghilangkan segmen garis penghubung apa pun. Jika metode pembuatan jalur sebelumnya di jalur saat ini juga "MoveTo", "MoveTo" baru akan menimpanya; tidak ada sisa dari operasi "MoveTo" sebelumnya yang tersisa di jalur. |
| override [RestoreGraphicContext](../../aspose.html.rendering.xps/xpsdevice/restoregraphiccontext/)() | Mengembalikan seluruh konteks grafik ke nilai sebelumnya dengan mengeluarkannya dari tumpukan. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| override [Stroke](../../aspose.html.rendering.xps/xpsdevice/stroke/)() | Memotong garis di sepanjang jalur saat ini. Garis yang digores mengikuti setiap segmen lurus atau melengkung di jalur, berpusat pada segmen dengan sisi sejajar dengannya. Setiap subjalur jalur diperlakukan secara terpisah. Metode ini menghentikan jalur saat ini. |
| override [StrokeAndFill](../../aspose.html.rendering.xps/xpsdevice/strokeandfill/)(FillMode) | Goresan dan isi jalur saat ini. Metode ini mengakhiri jalur saat ini. |
| override [StrokeText](../../aspose.html.rendering.xps/xpsdevice/stroketext/)(string, PointF) | Memotong string teks yang ditentukan di lokasi yang ditentukan. |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext/) | Menyimpan parameter kontrol grafis saat ini untuk XpsDevice. Parameter ini menentukan kerangka kerja global tempat operator grafis mengeksekusi. |

### Lihat juga

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* ruang nama [Aspose.Html.Rendering.Xps](../../aspose.html.rendering.xps/)
* perakitan [Aspose.HTML](../../)


