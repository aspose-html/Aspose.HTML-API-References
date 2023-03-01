---
title: SVGTransform.Matrix
second_title: Aspose.HTML untuk Referensi .NET API
description: SVGTransform Properti. Matriks yang mewakili transformasi ini. Objek matriks hidup artinya setiap perubahan yang dilakukan pada objek SVGTransform segera tercermin dalam objek matriks dan sebaliknya. Jika objek matriks diubah secara langsung yaitu tanpa menggunakan metode pada antarmuka SVGTransform itu sendiri maka tipe SVGTransform berubah menjadi SVG_TRANSFORM_MATRIX. Untuk SVG_TRANSFORM_MATRIX matriks berisi a b c d e f nilai yang diberikan oleh pengguna. Untuk SVG_TRANSFORM_TRANSLATE e dan f merepresentasikan besaran translasia 1 b 0 c 0 dan d  1. Untuk SVG_TRANSFORM_SCALE a dan d merepresentasikan besaran skalab 0  c 0 e 0 dan f  0. Untuk SVG_TRANSFORM_SKEWX dan SVG_TRANSFORM_SKEWY a b c dan d mewakili matriks yang akan menghasilkan kemiringan yang diberikan e 0 dan f  0. Untuk SVG_TRANSFORM_ROTATE  a b c d e dan f bersamasama mewakili matriks yang akan menghasilkan rotasi yang diberikan. Ketika rotasi berada di sekitar titik pusat 0 0 e dan f akan menjadi nol.
type: docs
weight: 20
url: /id/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Matriks yang mewakili transformasi ini. Objek matriks hidup, artinya setiap perubahan yang dilakukan pada objek SVGTransform segera tercermin dalam objek matriks dan sebaliknya. Jika objek matriks diubah secara langsung (yaitu, tanpa menggunakan metode pada antarmuka SVGTransform itu sendiri) maka tipe SVGTransform berubah menjadi SVG_TRANSFORM_MATRIX. Untuk SVG_TRANSFORM_MATRIX, matriks berisi a, b, c, d, e, f nilai yang diberikan oleh pengguna. Untuk SVG_TRANSFORM_TRANSLATE, e dan f merepresentasikan besaran translasi(a= 1, b= 0, c= 0 dan d = 1). Untuk SVG_TRANSFORM_SCALE, a dan d merepresentasikan besaran skala(b= 0 , c= 0, e= 0 dan f = 0). Untuk SVG_TRANSFORM_SKEWX dan SVG_TRANSFORM_SKEWY, a, b, c dan d mewakili matriks yang akan menghasilkan kemiringan yang diberikan (e= 0 dan f = 0). Untuk SVG_TRANSFORM_ROTATE , a, b, c, d, e dan f bersama-sama mewakili matriks yang akan menghasilkan rotasi yang diberikan. Ketika rotasi berada di sekitar titik pusat (0, 0), e dan f akan menjadi nol.

```csharp
public SVGMatrix Matrix { get; }
```

### Nilai properti

Matriks yang mewakili transformasi ini.

### Lihat juga

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* ruang nama [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* perakitan [Aspose.HTML](../../../)


