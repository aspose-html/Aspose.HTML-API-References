---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D antarmuka. Antarmuka ICanvasRenderingContext2D digunakan untuk menggambar persegi panjang teks gambar dan objek lain ke elemen kanvas. Ini memberikan konteks rendering 2D untuk permukaan gambar elemen kanvas.
type: docs
weight: 260
url: /id/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

Antarmuka ICanvasRenderingContext2D digunakan untuk menggambar persegi panjang, teks, gambar, dan objek lain ke elemen kanvas. Ini memberikan konteks rendering 2D untuk permukaan gambar elemen kanvas.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | Referensi balik hanya-baca ke HTMLCanvasElement. Mungkin nol jika tidak dikaitkan dengan elemen kanvas. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Warna atau gaya untuk digunakan di dalam bentuk. Bawaan: (hitam). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Nilai alfa yang diterapkan ke bentuk dan gambar sebelum digabungkan ke kanvas. Standar 1.0 (buram). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | Dengan penerapan globalAlpha ini mengatur bagaimana bentuk dan gambar digambar ke bitmap yang ada. Default: (dari sumber) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Mode perataan gambar; jika dinonaktifkan, gambar tidak akan dihaluskan jika diskalakan. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Menentukan efek buram. 0 bawaan |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Warna bayangan. Hitam standar sepenuhnya transparan. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Jarak horizontal bayangan akan diimbangi. Standar 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Jarak vertikal bayangan akan diimbangi. Standar 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Warna atau gaya yang digunakan untuk garis di sekitar bentuk. Bawaan: (hitam). |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Menambahkan wilayah klik ke kanvas. Ini memungkinkan Anda untuk mempermudah deteksi klik, memungkinkan Anda merutekan peristiwa ke elemen DOM, dan memungkinkan pengguna menjelajahi kanvas tanpa melihatnya. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Memulai jalur baru dengan mengosongkan daftar sub-jalur. Panggil metode ini saat Anda ingin membuat jalur baru. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Menghapus semua wilayah klik dari kanvas. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Menyetel semua piksel dalam persegi panjang yang ditentukan oleh titik awal (x, y) dan ukuran (lebar, tinggi) menjadi hitam transparan, menghapus konten yang digambar sebelumnya. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Membuat wilayah kliping baru dengan menghitung persimpangan wilayah kliping saat ini dan area yang dijelaskan oleh jalur, menggunakan aturan angka belitan bukan nol. Buka subjalur harus ditutup secara implisit saat menghitung wilayah kliping, tanpa memengaruhi subjalur yang sebenarnya . Wilayah kliping baru menggantikan wilayah kliping saat ini. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Membuat wilayah kliping baru dengan menghitung persimpangan wilayah kliping saat ini dan area yang dijelaskan oleh jalur, menggunakan aturan angka lilitan bukan nol. Subjalur terbuka harus ditutup secara implisit saat menghitung wilayah kliping, tanpa memengaruhi subjalur sebenarnya. Wilayah kliping baru menggantikan wilayah kliping saat ini. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Membuat wilayah kliping baru dengan menghitung persimpangan wilayah kliping saat ini dan area yang dijelaskan oleh jalur, menggunakan aturan angka lilitan bukan nol. Subjalur terbuka harus ditutup secara implisit saat menghitung wilayah kliping, tanpa memengaruhi subjalur sebenarnya. Wilayah kliping baru menggantikan wilayah kliping saat ini. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Membuat objek ImageData kosong baru dengan dimensi yang ditentukan. Semua piksel dalam objek baru berwarna hitam transparan. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Membuat objek ImageData kosong baru dengan dimensi yang ditentukan. Semua piksel dalam objek baru berwarna hitam transparan. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Membuat gradien linier sepanjang garis yang diberikan oleh koordinat yang diwakili oleh parameter. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Membuat pola menggunakan gambar yang ditentukan (sebuah CanvasImageSource). Ini mengulangi sumber ke arah yang ditentukan oleh argumen pengulangan. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Membuat pola menggunakan gambar yang ditentukan (sebuah CanvasImageSource). Ini mengulangi sumber ke arah yang ditentukan oleh argumen pengulangan. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Membuat gradien radial yang diberikan oleh koordinat dua lingkaran yang diwakili oleh parameter. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Jika elemen tertentu difokuskan, metode ini menggambar cincin fokus di sekitar jalur saat ini. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Menggambar gambar yang ditentukan. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Menggambar gambar yang ditentukan. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Menggambar gambar yang ditentukan. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Menggambar gambar yang ditentukan. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Menggambar gambar yang ditentukan. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Menggambar gambar yang ditentukan. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Mengisi subjalur dengan gaya isian saat ini dan algoritme default CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Mengisi subjalur dengan gaya isian saat ini. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Mengisi subjalur dengan gaya isian saat ini dan algoritme default CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Mengisi subjalur dengan gaya isian saat ini. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Menggambar persegi panjang yang terisi pada posisi (x, y) yang ukurannya ditentukan oleh lebar dan tinggi. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Menggambar (mengisi) teks tertentu pada posisi (x,y) tertentu. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Menggambar (mengisi) teks tertentu pada posisi (x,y) tertentu. |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Mengembalikan objek ImageData yang mewakili data piksel dasar untuk area kanvas yang dilambangkan dengan persegi panjang yang dimulai dari (sx, sy) dan memiliki lebar sw dan tinggi sh. Metode ini tidak terpengaruh oleh matriks transformasi kanvas. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Melaporkan apakah titik yang ditentukan terkandung di jalur saat ini atau tidak. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Melaporkan apakah titik yang ditentukan terkandung di jalur saat ini atau tidak. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Melaporkan apakah titik yang ditentukan terkandung di jalur saat ini atau tidak. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Melaporkan apakah titik yang ditentukan terkandung di jalur saat ini atau tidak. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Melaporkan apakah titik yang ditentukan berada di dalam area yang dikandung oleh guratan suatu jalur atau tidak. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Melaporkan apakah titik yang ditentukan berada di dalam area yang dikandung oleh guratan suatu jalur atau tidak. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Mengembalikan objek TextMetrics. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Cat data dari objek ImageData yang diberikan ke bitmap. Jika persegi panjang kotor disediakan, hanya piksel dari persegi panjang itu yang dicat. Metode ini tidak terpengaruh oleh matriks transformasi kanvas. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Cat data dari objek ImageData yang diberikan ke bitmap. Jika persegi panjang kotor disediakan, hanya piksel dari persegi panjang itu yang dicat. Metode ini tidak terpengaruh oleh matriks transformasi kanvas. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Menghapus wilayah klik dengan id yang ditentukan dari kanvas. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Mereset transformasi saat ini dengan matriks identitas. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Mengembalikan status gaya gambar ke elemen terakhir pada 'tumpukan status' yang disimpan oleh save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Menambahkan rotasi ke matriks transformasi. Argumen sudut mewakili sudut rotasi searah jarum jam dan dinyatakan dalam radian. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Menyimpan status gaya gambar saat ini menggunakan tumpukan sehingga Anda dapat mengembalikan setiap perubahan yang Anda buat menggunakan restore(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Menambahkan transformasi penskalaan ke unit kanvas dengan x secara horizontal dan dengan y secara vertikal. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Mereset transformasi saat ini ke matriks identitas, lalu memanggil metode transform() dengan argumen yang sama. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Menggores subjalur dengan gaya goresan saat ini. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Menggores subjalur dengan gaya goresan saat ini. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Melukis persegi panjang yang memiliki titik awal di (x, y) dan memiliki lebar aw dan tinggi h pada kanvas, menggunakan gaya goresan saat ini. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Menggambar (goresan) teks tertentu pada posisi (x, y) yang diberikan. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Menggambar (goresan) teks tertentu pada posisi (x, y) yang diberikan. |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Mengalikan matriks transformasi saat ini dengan matriks yang dijelaskan oleh argumennya. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Menambahkan transformasi terjemahan dengan memindahkan kanvas dan asal x secara horizontal dan y secara vertikal pada kisi. |

### Lihat juga

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* ruang nama [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* perakitan [Aspose.HTML](../../)


