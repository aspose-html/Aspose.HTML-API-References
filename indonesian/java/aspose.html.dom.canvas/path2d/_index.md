---
title: "Kelas Path2D"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.canvas.Path2D kelas. Antarmuka Path2D dari Canvas 2D API digunakan untuk mendeklarasikan jalur yang kemudian nanti digunakan pada objek CanvasRenderingContext2D. Metode jalur dari antarmuka CanvasRenderingContext2D juga tersedia pada antarmuka ini dan memungkinkan Anda membuat jalur yang dapat dipertahankan dan diputar ulang sesuai kebutuhan pada kanvas."
type: docs

url: /id/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Antarmuka Path2D dari Canvas 2D API digunakan untuk mendeklarasikan jalur yang kemudian akan digunakan pada objek CanvasRenderingContext2D. Metode jalur dari antarmuka CanvasRenderingContext2D juga hadir pada antarmuka ini dan memungkinkan Anda membuat jalur yang dapat disimpan dan diputar ulang sesuai kebutuhan pada kanvas.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Path2D](path2d/#constructor)() | mengembalikan objek Path2D yang baru diinstansiasi |
| [Path2D](path2d/#constructor_1)(Path2D) | mengembalikan objek Path2D yang baru diinstansiasi dengan jalur lain sebagai argumen (membuat salinan) |
| [Path2D](path2d/#constructor_2)(String) | mengembalikan objek Path2D yang baru diinstansiasi dengan String yang berisi data jalur SVG. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Menambahkan ke jalur jalur yang diberikan oleh argumen. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Menambahkan ke jalur jalur yang diberikan oleh argumen. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Menambahkan busur ke jalur yang berpusat pada posisi (x, y) dengan jari-jari r mulai dari startAngle hingga endAngle bergerak dalam arah yang diberikan secara berlawanan arah jarum jam (default ke arah jarum jam). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Menambahkan busur ke jalur yang berpusat pada posisi (x, y) dengan jari-jari r mulai dari startAngle hingga endAngle bergerak dalam arah yang diberikan secara berlawanan arah jarum jam (default ke arah jarum jam). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Menambahkan busur ke jalur dengan titik kontrol dan jari-jari yang diberikan, terhubung ke titik sebelumnya dengan garis lurus. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Menambahkan kurva Bézier kubik ke jalur. Kurva ini memerlukan tiga titik. Dua titik pertama adalah titik kontrol dan titik ketiga adalah titik akhir. Titik awal adalah titik terakhir dalam jalur saat ini, yang dapat diubah menggunakan moveTo() sebelum membuat kurva Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Menyebabkan titik pena bergerak kembali ke awal sub‑jalur saat ini. Ini mencoba menggambar garis lurus dari titik saat ini ke awal. Jika bentuk sudah ditutup atau hanya memiliki satu titik, fungsi ini tidak melakukan apa‑apa. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Membuang objek. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Menambahkan elips ke jalur yang berpusat pada posisi (x, y) dengan radius radiusX dan radiusY mulai dari startAngle hingga endAngle bergerak dalam arah yang diberikan secara berlawanan arah jarum jam (default ke arah jarum jam). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Menambahkan elips ke jalur yang berpusat pada posisi (x, y) dengan radius radiusX dan radiusY mulai dari startAngle hingga endAngle bergerak dalam arah yang diberikan secara berlawanan arah jarum jam (default ke arah jarum jam). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Menghubungkan titik terakhir dalam sub‑jalur ke koordinat x, y dengan garis lurus. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Memindahkan titik awal sub‑jalur baru ke koordinat (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Menambahkan kurva Bézier kuadratik ke jalur saat ini. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Membuat jalur untuk persegi panjang pada posisi (x, y) dengan ukuran yang ditentukan oleh lebar dan tinggi. |

### Lihat Juga

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
