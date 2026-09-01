---
title: "Antarmuka IDevice"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.rendering.IDevice. Mendefinisikan metode dan properti yang mendukung rendering khusus elemen grafis seperti jalur, teks, dan gambar"
type: docs

url: /id/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Mendefinisikan metode dan properti yang mendukung rendering khusus elemen grafis seperti jalur, teks, dan gambar.

```java
public interface IDevice : IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Mendapatkan konteks grafis. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Mendapatkan opsi rendering. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Menambahkan persegi panjang ke jalur saat ini sebagai subpath lengkap. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Memulai rendering dokumen. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Memulai rendering elemen. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Memulai rendering halaman baru. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Memodifikasi jalur pemotongan saat ini dengan menginterseksikannya dengan jalur saat ini, menggunakan FillRule untuk menentukan wilayah yang akan diisi. Metode ini mengakhiri jalur saat ini. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Menutup subpath saat ini dengan menambahkan segmen garis lurus dari titik saat ini ke titik awal subpath. Jika subpath saat ini sudah tertutup, \"ClosePath\" tidak melakukan apa-apa. Operator ini mengakhiri subpath saat ini. Menambahkan segmen lain ke jalur saat ini memulai subpath baru, bahkan jika segmen baru dimulai pada titik akhir yang dicapai oleh metode \"ClosePath\". |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Menambahkan kurva Bézier kubik ke jalur saat ini. Kurva tersebut memperluas dari titik saat ini ke titik pt3, menggunakan pt1 dan pt2 sebagai titik kontrol Bézier. Titik saat ini yang baru adalah pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Menggambar gambar yang ditentukan. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Mengakhiri rendering dokumen. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Mengakhiri rendering elemen. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Mengakhiri rendering halaman saat ini. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Mengisi seluruh wilayah yang dikelilingi oleh jalur saat ini. Jika jalur terdiri dari beberapa subjalur yang terputus, ia mengisi bagian dalam semua subjalur, dipertimbangkan bersama. Metode ini mengakhiri jalur saat ini. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Mengisi String teks yang ditentukan pada lokasi yang ditentukan. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Membuang semua data ke aliran output. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Menambahkan segmen garis lurus dari titik saat ini ke titik (pt). Titik saat ini yang baru adalah pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Memulai subjalur baru dengan memindahkan titik saat ini ke koordinat parameter pt, tanpa menambahkan segmen garis penghubung. Jika metode konstruksi jalur sebelumnya dalam jalur saat ini juga "MoveTo", "MoveTo" baru akan menggantikannya; tidak ada jejak operasi "MoveTo" sebelumnya yang tersisa dalam jalur. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Mengembalikan seluruh konteks grafis ke nilai sebelumnya dengan mengeluarkannya dari tumpukan. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Mendorong salinan seluruh konteks grafis ke tumpukan. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Menggambar garis sepanjang jalur saat ini. Garis yang digambar mengikuti setiap segmen lurus atau melengkung dalam jalur, berpusat pada segmen dengan sisi yang paralel. Setiap subjalur jalur diperlakukan secara terpisah. Metode ini mengakhiri jalur saat ini. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Menggambar dan mengisi jalur saat ini. Metode ini mengakhiri jalur saat ini. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Menggambar String teks yang ditentukan pada lokasi yang ditentukan. |

### Lihat Juga

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
