---
title: "Kelas SVGMatrix"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.svg.datatypes.SVGMatrix. Banyak operasi grafis SVG menggunakan matriks 2x3 dengan bentuk a c e b d f yang ketika diperluas menjadi matriks 3x3 untuk keperluan aritmetika matriks menjadi a c e b d f 0 0 1"
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Banyak operasi grafis SVG menggunakan matriks 2x3 dengan bentuk: [a c e] [b d f] yang, ketika diperluas menjadi matriks 3x3 untuk keperluan aritmetika matriks, menjadi: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | Komponen A dari matriks. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | Komponen B dari matriks. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | Komponen C dari matriks. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | Komponen D dari matriks. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | Komponen E dari matriks. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | Komponen F dari matriks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Melepaskan sumber daya yang tidak terkelola dan - secara opsional - terkelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Melakukan perkalian matriks. Matriks ini dipost-multiplikasikan dengan matriks lain, mengembalikan matriks baru yang dihasilkan. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Memost-multiplikasikan transformasi rotasi pada matriks saat ini dan mengembalikan matriks yang dihasilkan. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Memost-multiplikasikan transformasi skala seragam pada matriks saat ini dan mengembalikan matriks yang dihasilkan. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Memost-multiplikasikan transformasi skala tidak seragam pada matriks saat ini dan mengembalikan matriks yang dihasilkan. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Melakukan perkalian pasca pada transformasi skewX pada matriks saat ini dan mengembalikan matriks hasilnya. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Melakukan perkalian pasca pada transformasi skewY pada matriks saat ini dan mengembalikan matriks hasilnya. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Mengembalikan String yang mewakili instance ini. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Melakukan perkalian pasca pada transformasi translasi pada matriks saat ini dan mengembalikan matriks hasilnya. |

### Lihat Juga

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
