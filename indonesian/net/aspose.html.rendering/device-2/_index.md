---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions kelas. Merupakan kelas dasar untuk implementasi perangkat rendering tertentu.
type: docs
weight: 4140
url: /id/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Merupakan kelas dasar untuk implementasi perangkat rendering tertentu.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Keterangan |
| --- | --- |
| TGraphicContext | Konteks grafis yang menyimpan parameter kontrol grafis saat ini |
| TRenderingOptions | Opsi rendering |

## Properti

| Nama | Keterangan |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | Mendapatkan konteks grafik |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | Mendapat opsi rendering. |

## Metode

| Nama | Keterangan |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | Menambahkan persegi panjang ke jalur saat ini sebagai subjalur lengkap. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | Memulai rendering dokumen. |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Memulai rendering node. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | Memulai rendering halaman baru. |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | Memodifikasi jalur kliping saat ini dengan memotongnya dengan jalur saat ini, menggunakan aturan FillMode untuk menentukan wilayah yang akan diisi. Metode ini menghentikan jalur saat ini. |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | Menutup subjalur saat ini dengan menambahkan segmen garis lurus dari titik saat ini ke titik awal subjalur. Jika subjalur saat ini sudah ditutup, "ClosePath" tidak melakukan apa pun. Operator ini menghentikan subjalur saat ini. Menambahkan segmen lain ke jalur saat ini memulai subjalur baru, bahkan jika segmen baru dimulai pada titik akhir yang dijangkau oleh metode "ClosePath". |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Menambahkan kurva Bézier kubik ke jalur saat ini. Kurva memanjang dari titik saat ini ke titik pt2, menggunakan pt1 dan pt2 sebagai titik kontrol Bézier. Titik baru saat ini adalah pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau menyetel ulang sumber daya yang tidak dikelola. |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | Menggambar gambar yang ditentukan. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | Mengakhiri rendering dokumen. |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | Mengakhiri rendering node. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | Mengakhiri rendering halaman saat ini. |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | Mengisi seluruh wilayah yang dilingkupi oleh jalur saat ini. Jika jalur terdiri dari beberapa subjalur yang terputus, jalur tersebut mengisi bagian dalam semua subjalur, dipertimbangkan bersama. Metode ini menghentikan jalur saat ini. |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | Mengisi string teks yang ditentukan di lokasi yang ditentukan. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | Membuang semua data ke aliran keluaran. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | Menambahkan segmen garis lurus dari titik saat ini ke titik (pt). Titik baru saat ini adalah pt. |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | Memulai subjalur baru dengan memindahkan titik saat ini ke koordinat parameter pt, menghilangkan segmen garis penghubung apa pun. Jika metode pembuatan jalur sebelumnya di jalur saat ini juga "MoveTo", "MoveTo" baru akan menimpanya; tidak ada sisa dari operasi "MoveTo" sebelumnya yang tersisa di jalur. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | Mengembalikan seluruh konteks grafik ke nilai sebelumnya dengan mengeluarkannya dari tumpukan. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | Mendorong salinan seluruh konteks grafik ke tumpukan. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | Memotong garis di sepanjang jalur saat ini. Garis yang digores mengikuti setiap segmen lurus atau melengkung di jalur, berpusat pada segmen dengan sisi sejajar dengannya. Setiap subjalur jalur diperlakukan secara terpisah. Metode ini menghentikan jalur saat ini. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | Goresan dan isi jalur saat ini. Metode ini mengakhiri jalur saat ini. |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | Memotong string teks yang ditentukan di lokasi yang ditentukan. |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | Merupakan objek konfigurasi untuk perangkat. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | Menentukan jenis strategi untuk menulis halaman ke aliran keluaran\aliran. |

### Lihat juga

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* ruang nama [Aspose.Html.Rendering](../../aspose.html.rendering/)
* perakitan [Aspose.HTML](../../)


