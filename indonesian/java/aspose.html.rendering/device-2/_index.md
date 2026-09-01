---
title: "Kelas DeviceTGraphicContextTRenderingOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions. Mewakili kelas dasar untuk implementasi perangkat rendering tertentu"
type: docs

url: /id/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Mewakili kelas dasar untuk implementasi perangkat rendering tertentu.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Deskripsi |
| --- | --- |
| TGraphicContext | Konteks grafis yang menyimpan parameter kontrol grafis saat ini |
| TRenderingOptions | Opsi rendering |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Mendapatkan konteks grafis |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Mendapatkan opsi rendering. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Menambahkan persegi panjang ke jalur saat ini sebagai subpath lengkap. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Memulai rendering dokumen. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Memulai rendering node. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Memulai rendering halaman baru. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Memodifikasi jalur pemotongan saat ini dengan menginterseksikannya dengan jalur saat ini, menggunakan FillRule untuk menentukan wilayah yang akan diisi. Metode ini mengakhiri jalur saat ini. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Menutup subpath saat ini dengan menambahkan segmen garis lurus dari titik saat ini ke titik awal subpath. Jika subpath saat ini sudah tertutup, \"ClosePath\" tidak melakukan apa-apa. Operator ini mengakhiri subpath saat ini. Menambahkan segmen lain ke jalur saat ini memulai subpath baru, bahkan jika segmen baru dimulai pada titik akhir yang dicapai oleh metode \"ClosePath\". |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Menambahkan kurva Bézier kubik ke jalur saat ini. Kurva tersebut meluas dari titik saat ini ke titik pt2, menggunakan pt1 dan pt2 sebagai titik kontrol Bézier. Titik saat ini yang baru adalah pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan pembebasan, pelepasan, atau pengaturan ulang sumber daya yang tidak dikelola. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Menggambar gambar yang ditentukan. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Mengakhiri rendering dokumen. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Mengakhiri rendering node. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Mengakhiri rendering halaman saat ini. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Mengisi seluruh wilayah yang dikelilingi oleh jalur saat ini. Jika jalur terdiri dari beberapa subjalur yang terputus, ia mengisi bagian dalam semua subjalur, dipertimbangkan bersama. Metode ini mengakhiri jalur saat ini. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Mengisi String teks yang ditentukan pada lokasi yang ditentukan. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Membuang semua data ke aliran output. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Menambahkan segmen garis lurus dari titik saat ini ke titik (pt). Titik saat ini yang baru adalah pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Memulai subjalur baru dengan memindahkan titik saat ini ke koordinat parameter pt, tanpa menambahkan segmen garis penghubung. Jika metode konstruksi jalur sebelumnya dalam jalur saat ini juga "MoveTo", "MoveTo" baru akan menggantikannya; tidak ada jejak operasi "MoveTo" sebelumnya yang tersisa dalam jalur. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Mengembalikan seluruh konteks grafis ke nilai sebelumnya dengan mengeluarkannya dari tumpukan. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Mendorong salinan seluruh konteks grafis ke tumpukan. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Menggambar garis sepanjang jalur saat ini. Garis yang digambar mengikuti setiap segmen lurus atau melengkung dalam jalur, berpusat pada segmen dengan sisi yang paralel. Setiap subjalur jalur diperlakukan secara terpisah. Metode ini mengakhiri jalur saat ini. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Menggambar dan mengisi jalur saat ini. Metode ini mengakhiri jalur saat ini. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Menggambar String teks yang ditentukan pada lokasi yang ditentukan. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Menentukan jenis strategi untuk menulis halaman ke aliran output\streams. |

### Lihat Juga

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
