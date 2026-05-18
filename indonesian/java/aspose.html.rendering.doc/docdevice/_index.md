---
title: "DocDevice Class"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.rendering.doc.DocDevice. Mewakili rendering ke dokumen DOCX"
type: docs

url: /id/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Mewakili proses rendering ke dokumen DOCX.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Menginisialisasi sebuah instance baru dari kelas `DocDevice`. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Menginisialisasi sebuah instance baru dari kelas `DocDevice` melalui aliran output. |
| [DocDevice](docdevice/#constructor_5)(String) | Menginisialisasi sebuah instance baru dari kelas `DocDevice` melalui nama file output. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Menginisialisasi sebuah instance baru dari kelas `DocDevice` dengan opsi rendering dan penyedia aliran. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Menginisialisasi sebuah instance baru dari kelas `DocDevice` dengan opsi rendering dan aliran output. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Menginisialisasi sebuah instance baru dari kelas `DocDevice` dengan opsi rendering dan nama file output. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Menambahkan sebuah persegi panjang ke jalur saat ini sebagai subpath lengkap. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Memulai rendering dokumen. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Memulai rendering node html. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Memulai rendering halaman baru. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Memodifikasi jalur pemotongan saat ini dengan memotongnya bersama jalur saat ini, menggunakan aturan FillMode untuk menentukan wilayah yang akan diisi. Metode ini mengakhiri jalur saat ini. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Menutup subpath saat ini dengan menambahkan segmen garis lurus dari titik saat ini ke titik awal subpath. Jika subpath saat ini sudah tertutup, \"ClosePath\" tidak melakukan apa pun. Operator ini mengakhiri subpath saat ini. Menambahkan segmen lain ke jalur saat ini memulai subpath baru, bahkan jika segmen baru dimulai pada titik akhir yang dicapai oleh metode \"ClosePath\". |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Menambahkan kurva Bézier kubik ke jalur saat ini. Kurva tersebut meluas dari titik saat ini ke titik pt2, menggunakan pt1 dan pt2 sebagai titik kontrol Bézier. Titik saat ini yang baru adalah pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Menggambar gambar yang ditentukan. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Mengakhiri rendering node html. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Mengakhiri proses rendering halaman saat ini. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Mengisi seluruh wilayah yang dibatasi oleh jalur saat ini. Jika jalur terdiri dari beberapa sub‑jalur yang tidak terhubung, ia mengisi bagian dalam semua sub‑jalur secara bersamaan. Metode ini mengakhiri jalur saat ini. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Mengisi String teks yang ditentukan pada lokasi yang ditentukan. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Membuang semua data ke aliran output. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Menambahkan segmen garis lurus dari titik saat ini ke titik (pt). Titik saat ini yang baru adalah pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Memulai sub‑jalur baru dengan memindahkan titik saat ini ke koordinat parameter pt, tanpa menambahkan segmen garis penghubung. Jika metode konstruksi jalur sebelumnya dalam jalur saat ini juga "MoveTo", maka "MoveTo" baru akan menggantikannya; tidak ada jejak operasi "MoveTo" sebelumnya yang tersisa dalam jalur. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Menggambar garis sepanjang jalur saat ini. Garis yang digambar mengikuti setiap segmen lurus atau melengkung dalam jalur, berpusat pada segmen dengan sisi yang paralel dengannya. Setiap sub‑jalur jalur diperlakukan secara terpisah. Metode ini mengakhiri jalur saat ini. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Menggambar dan mengisi jalur saat ini. Metode ini mengakhiri jalur saat ini. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Menggambar String teks yang ditentukan pada lokasi yang ditentukan. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Menyimpan parameter kontrol grafis saat ini untuk DocDevice. Parameter ini mendefinisikan kerangka kerja global tempat operator grafis dijalankan. |

### Lihat Juga

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
