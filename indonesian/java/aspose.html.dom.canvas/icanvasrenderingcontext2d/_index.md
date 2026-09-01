---
title: "Antarmuka ICanvasRenderingContext2D"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.canvas.ICanvasRenderingContext2D. Antarmuka ICanvasRenderingContext2D digunakan untuk menggambar persegi panjang, teks, gambar, dan objek lain ke elemen kanvas. Ini menyediakan konteks rendering 2D untuk permukaan gambar elemen kanvas."
type: docs

url: /id/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

Antarmuka ICanvasRenderingContext2D digunakan untuk menggambar persegi panjang, teks, gambar, dan objek lain ke elemen canvas. Ia menyediakan konteks rendering 2D untuk permukaan gambar dari elemen canvas.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) Referensi balik hanya-baca ke HTMLCanvasElement. Mungkin null jika tidak terkait dengan elemen kanvas. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Memulai jalur baru dengan mengosongkan daftar sub‑jalur. Panggil metode ini ketika Anda ingin membuat jalur baru. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Menghapus semua wilayah hit dari kanvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Mengatur semua piksel dalam persegi panjang yang didefinisikan oleh titik awal (x, y) dan ukuran (lebar, tinggi) menjadi hitam transparan, menghapus konten yang sebelumnya digambar. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Membuat wilayah pemotongan baru dengan menghitung irisan antara wilayah pemotongan saat ini dan area yang dijelaskan oleh jalur, menggunakan aturan nomor lilitan non‑nol. Sub‑jalur terbuka harus ditutup secara implisit saat menghitung wilayah pemotongan, tanpa memengaruhi sub‑jalur sebenarnya. Wilayah pemotongan baru menggantikan wilayah pemotongan saat ini. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Membuat wilayah pemotongan baru dengan menghitung irisan antara wilayah pemotongan saat ini dan area yang dijelaskan oleh jalur, menggunakan aturan nomor lilitan non‑nol. Sub‑jalur terbuka harus ditutup secara implisit saat menghitung wilayah pemotongan, tanpa memengaruhi sub‑jalur sebenarnya. Wilayah pemotongan baru menggantikan wilayah pemotongan saat ini. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Membuat wilayah pemotongan baru dengan menghitung irisan antara wilayah pemotongan saat ini dan area yang dijelaskan oleh jalur, menggunakan aturan nomor lilitan non‑nol. Sub‑jalur terbuka harus ditutup secara implisit saat menghitung wilayah pemotongan, tanpa memengaruhi sub‑jalur sebenarnya. Wilayah pemotongan baru menggantikan wilayah pemotongan saat ini. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Membuat objek ImageData baru yang kosong dengan dimensi yang ditentukan. Semua piksel dalam objek baru tersebut berwarna hitam transparan. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Membuat objek ImageData baru yang kosong dengan dimensi yang ditentukan. Semua piksel dalam objek baru tersebut berwarna hitam transparan. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Membuat gradien linear sepanjang garis yang diberikan oleh koordinat yang direpresentasikan oleh parameter. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Membuat pola menggunakan gambar yang ditentukan (CanvasImageSource). Gambar sumber diulang pada arah yang ditentukan oleh argumen pengulangan. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Membuat pola menggunakan gambar yang ditentukan (CanvasImageSource). Gambar sumber diulang pada arah yang ditentukan oleh argumen pengulangan. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Membuat gradien radial yang diberikan oleh koordinat dua lingkaran yang direpresentasikan oleh parameter. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Jika sebuah elemen berada dalam fokus, metode ini menggambar cincin fokus di sekitar jalur saat ini. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Menggambar gambar yang ditentukan. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Menggambar gambar yang ditentukan. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Menggambar gambar yang ditentukan. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Menggambar gambar yang ditentukan. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Menggambar gambar yang ditentukan. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Menggambar gambar yang ditentukan. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Mengisi subjalur dengan gaya isi saat ini dan algoritma default CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Mengisi subjalur dengan gaya isi saat ini. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Mengisi subjalur dengan gaya isi saat ini dan algoritma default CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Mengisi subjalur dengan gaya isi saat ini. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Menggambar persegi panjang terisi pada posisi (x, y) yang ukurannya ditentukan oleh lebar dan tinggi. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Menggambar (mengisi) teks yang diberikan pada posisi (x,y) yang diberikan. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Menggambar (mengisi) teks yang diberikan pada posisi (x,y) yang diberikan. |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Mengembalikan objek ImageData yang mewakili data piksel dasar untuk area kanvas yang ditandai oleh persegi panjang yang dimulai pada (sx, sy) dan memiliki lebar sw serta tinggi sh. Metode ini tidak dipengaruhi oleh matriks transformasi kanvas. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Melaporkan apakah titik yang ditentukan berada di dalam jalur saat ini atau tidak. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Melaporkan apakah titik yang ditentukan berada di dalam jalur saat ini atau tidak. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Melaporkan apakah titik yang ditentukan berada di dalam jalur saat ini atau tidak. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Melaporkan apakah titik yang ditentukan berada di dalam jalur saat ini atau tidak. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Melaporkan apakah titik yang ditentukan berada di dalam area yang tercakup oleh goresan jalur atau tidak. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Melaporkan apakah titik yang ditentukan berada di dalam area yang tercakup oleh goresan jalur atau tidak. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Mengembalikan objek TextMetrics. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Melukis data dari objek ImageData yang diberikan ke bitmap. Jika persegi panjang kotor disediakan, hanya piksel dari persegi panjang itu yang dilukis. Metode ini tidak dipengaruhi oleh matriks transformasi kanvas. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Melukis data dari objek ImageData yang diberikan ke bitmap. Jika persegi panjang kotor disediakan, hanya piksel dari persegi panjang itu yang dilukis. Metode ini tidak dipengaruhi oleh matriks transformasi kanvas. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Menghapus wilayah hit dengan id yang ditentukan dari kanvas. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Mengatur ulang transformasi saat ini dengan matriks identitas. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Mengembalikan keadaan gaya menggambar ke elemen terakhir pada 'tumpukan status' yang disimpan oleh save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Menambahkan rotasi ke matriks transformasi. Argumen sudut mewakili sudut rotasi searah jarum jam dan dinyatakan dalam radian. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Menyimpan keadaan gaya menggambar saat ini menggunakan tumpukan sehingga Anda dapat mengembalikan perubahan apa pun yang Anda buat dengan menggunakan restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Menambahkan transformasi skala ke unit kanvas sebesar x secara horizontal dan y secara vertikal. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Mengatur ulang transformasi saat ini ke matriks identitas, lalu memanggil metode transform() dengan argumen yang sama. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Menggoreskan subjalur dengan gaya goresan saat ini. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Menggoreskan subjalur dengan gaya goresan saat ini. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Melukis persegi panjang yang memiliki titik awal pada (x, y) dan memiliki lebar w serta tinggi h ke kanvas, menggunakan gaya goresan saat ini. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Menggambar (menggoreskan) teks yang diberikan pada posisi (x, y) yang diberikan. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Menggambar (menggoreskan) teks yang diberikan pada posisi (x, y) yang diberikan. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Mengalikan matriks transformasi saat ini dengan matriks yang dijelaskan oleh argumennya. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Menambahkan transformasi translasi dengan memindahkan kanvas dan asalnya x secara horizontal dan y secara vertikal pada grid. |

### Lihat Juga

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
