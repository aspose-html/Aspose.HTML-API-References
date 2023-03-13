---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods antarmuka. Antarmuka ICanvasPathMethods digunakan untuk memanipulasi jalur objek.
type: docs
weight: 240
url: /id/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Antarmuka ICanvasPathMethods digunakan untuk memanipulasi jalur objek.

```csharp
public interface ICanvasPathMethods
```

## Metode

| Nama | Keterangan |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Menambahkan busur ke jalur yang berpusat pada posisi (x, y) dengan radius r mulai dari startAngle dan berakhir di endAngle menuju arah yang diberikan dengan berlawanan arah jarum jam (default ke searah jarum jam). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Menambahkan busur ke jalur yang berpusat pada posisi (x, y) dengan radius r mulai dari startAngle dan berakhir di endAngle menuju arah yang diberikan dengan berlawanan arah jarum jam (default ke searah jarum jam). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Menambahkan busur ke jalur dengan titik kontrol dan radius yang diberikan, terhubung ke titik sebelumnya dengan garis lurus. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Menambahkan kurva Bézier kubik ke jalur. Itu membutuhkan tiga poin. Dua titik pertama adalah titik kontrol dan titik ketiga adalah titik akhir. Titik awal adalah titik terakhir di jalur saat ini, yang dapat diubah menggunakan moveTo() sebelum membuat kurva Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Menyebabkan ujung pena bergerak kembali ke awal sub-jalur saat ini. Mencoba menggambar garis lurus dari titik saat ini ke awal. Jika bentuknya sudah ditutup atau hanya memiliki satu titik, fungsi ini tidak melakukan apa-apa. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Menambahkan elips ke jalur yang berpusat di posisi (x, y) dengan jari-jari radiusX dan radiusY mulai dari startAngle dan berakhir di endAngle menuju arah yang diberikan berlawanan arah jarum jam (defaultnya searah jarum jam). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Menambahkan elips ke jalur yang berpusat di posisi (x, y) dengan jari-jari radiusX dan radiusY mulai dari startAngle dan berakhir di endAngle menuju arah yang diberikan berlawanan arah jarum jam (defaultnya searah jarum jam). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Menghubungkan titik terakhir dalam subjalur ke koordinat x, y dengan garis lurus. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Memindahkan titik awal sub-jalur baru ke koordinat (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Menambahkan kurva Bézier kuadrat ke jalur saat ini. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Membuat path untuk persegi panjang pada posisi (x,y) dengan ukuran yang ditentukan oleh lebar dan tinggi. |

### Lihat juga

* ruang nama [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* perakitan [Aspose.HTML](../../)


