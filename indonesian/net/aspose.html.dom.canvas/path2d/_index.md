---
title: Class Path2D
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Canvas.Path2D kelas. Antarmuka Path2D dari Canvas 2D API digunakan untuk mendeklarasikan path yang nantinya akan digunakan pada objek CanvasRenderingContext2D. Metode jalur antarmuka CanvasRenderingContext2D juga ada di antarmuka ini dan memungkinkan Anda membuat jalur yang dapat dipertahankan dan diputar ulang sesuai kebutuhan di kanvas.
type: docs
weight: 290
url: /id/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Antarmuka Path2D dari Canvas 2D API digunakan untuk mendeklarasikan path yang nantinya akan digunakan pada objek CanvasRenderingContext2D. Metode jalur antarmuka CanvasRenderingContext2D juga ada di antarmuka ini dan memungkinkan Anda membuat jalur yang dapat dipertahankan dan diputar ulang sesuai kebutuhan di kanvas.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Path2D](path2d/#constructor)() | mengembalikan objek Path2D yang baru dibuat |
| [Path2D](path2d/#constructor_1)(Path2D) | mengembalikan objek Path2D yang baru dibuat dengan jalur lain sebagai argumen (membuat salinan) |
| [Path2D](path2d/#constructor_2)(string) | mengembalikan objek Path2D yang baru dibuat dengan string yang terdiri dari data jalur SVG. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Menambahkan ke jalur jalur yang diberikan oleh argumen. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Menambahkan ke jalur jalur yang diberikan oleh argumen. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Menambahkan busur ke jalur yang berpusat pada posisi (x, y) dengan radius r mulai dari startAngle dan berakhir di endAngle menuju arah yang diberikan dengan berlawanan arah jarum jam (default ke searah jarum jam). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Menambahkan busur ke jalur yang berpusat pada posisi (x, y) dengan radius r mulai dari startAngle dan berakhir di endAngle menuju arah yang diberikan dengan berlawanan arah jarum jam (default ke searah jarum jam). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Menambahkan busur ke jalur dengan titik kontrol dan radius yang diberikan, terhubung ke titik sebelumnya dengan garis lurus. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Menambahkan kurva Bézier kubik ke jalur. Itu membutuhkan tiga poin. Dua titik pertama adalah titik kontrol dan titik ketiga adalah titik akhir. Titik awal adalah titik terakhir di jalur saat ini, yang dapat diubah menggunakan moveTo() sebelum membuat kurva Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | Menyebabkan ujung pena bergerak kembali ke awal sub-jalur saat ini. Mencoba menggambar garis lurus dari titik saat ini ke awal. Jika bentuknya sudah ditutup atau hanya memiliki satu titik, fungsi ini tidak melakukan apa-apa. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | Membuang objek. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Menambahkan elips ke jalur yang berpusat di posisi (x, y) dengan jari-jari radiusX dan radiusY mulai dari startAngle dan berakhir di endAngle menuju arah yang diberikan berlawanan arah jarum jam (defaultnya searah jarum jam). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Menambahkan elips ke jalur yang berpusat di posisi (x, y) dengan jari-jari radiusX dan radiusY mulai dari startAngle dan berakhir di endAngle menuju arah yang diberikan berlawanan arah jarum jam (defaultnya searah jarum jam). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | Menghubungkan titik terakhir dalam subjalur ke koordinat x, y dengan garis lurus. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | Memindahkan titik awal sub-jalur baru ke koordinat (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Menambahkan kurva Bézier kuadrat ke jalur saat ini. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Membuat path untuk persegi panjang pada posisi (x,y) dengan ukuran yang ditentukan oleh lebar dan tinggi. |

### Lihat juga

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* ruang nama [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* perakitan [Aspose.HTML](../../)


