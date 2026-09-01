---
title: "Antarmuka ICanvasPathMethods"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.dom.canvas.ICanvasPathMethods. Antarmuka ICanvasPathMethods digunakan untuk memanipulasi jalur objek."
type: docs

url: /id/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Antarmuka ICanvasPathMethods digunakan untuk memanipulasi jalur objek.

```java
public interface ICanvasPathMethods
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Menambahkan busur ke jalur yang berpusat pada posisi (x, y) dengan jari-jari r, mulai dari startAngle dan berakhir pada endAngle bergerak dalam arah yang diberikan secara berlawanan arah jarum jam (default ke arah jarum jam). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Menambahkan busur ke jalur yang berpusat pada posisi (x, y) dengan jari-jari r, mulai dari startAngle dan berakhir pada endAngle bergerak dalam arah yang diberikan secara berlawanan arah jarum jam (default ke arah jarum jam). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Menambahkan busur ke jalur dengan titik kontrol dan jari-jari yang diberikan, terhubung ke titik sebelumnya dengan garis lurus. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Menambahkan kurva Bézier kubik ke jalur. Kurva ini memerlukan tiga titik. Dua titik pertama adalah titik kontrol dan titik ketiga adalah titik akhir. Titik mulai adalah titik terakhir dalam jalur saat ini, yang dapat diubah menggunakan moveTo() sebelum membuat kurva Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Menyebabkan titik pena kembali ke awal sub‑jalur saat ini. Ini mencoba menggambar garis lurus dari titik saat ini ke awal. Jika bentuk sudah ditutup atau hanya memiliki satu titik, fungsi ini tidak melakukan apa‑apa. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Menambahkan elips ke jalur yang berpusat pada posisi (x, y) dengan radius radiusX dan radiusY, mulai dari startAngle dan berakhir pada endAngle bergerak dalam arah yang diberikan secara berlawanan arah jarum jam (default ke arah jarum jam). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Menambahkan elips ke jalur yang berpusat pada posisi (x, y) dengan radius radiusX dan radiusY, mulai dari startAngle dan berakhir pada endAngle bergerak dalam arah yang diberikan secara berlawanan arah jarum jam (default ke arah jarum jam). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Menghubungkan titik terakhir dalam sub‑jalur ke koordinat x, y dengan garis lurus. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Memindahkan titik awal sub‑jalur baru ke koordinat (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Menambahkan kurva Bézier kuadratik ke jalur saat ini. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Membuat jalur untuk persegi panjang pada posisi (x, y) dengan ukuran yang ditentukan oleh lebar dan tinggi. |

### Lihat Juga

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
