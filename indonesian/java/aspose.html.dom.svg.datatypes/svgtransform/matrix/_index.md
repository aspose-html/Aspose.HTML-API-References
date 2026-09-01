---
title: "SVGTransform.Matrix"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti SVGTransform. Matriks yang mewakili transformasi ini. Objek matriks bersifat langsung (live) yang berarti setiap perubahan yang dilakukan pada objek SVGTransform langsung tercermin pada objek matriks dan sebaliknya. Jika objek matriks diubah secara langsung, yaitu tanpa menggunakan metode pada antarmuka SVGTransform itu sendiri, maka tipe SVGTransform berubah menjadi SVG_TRANSFORM_MATRIX. Untuk SVG_TRANSFORM_MATRIX, matriks berisi nilai a b c d e f yang diberikan oleh pengguna. Untuk SVG_TRANSFORM_TRANSLATE, e dan f mewakili jumlah translasi (a=1 b=0 c=0 dan d=1). Untuk SVG_TRANSFORM_SCALE, a dan d mewakili jumlah skala (b=0 c=0 e=0 dan f=0). Untuk SVG_TRANSFORM_SKEWX dan SVG_TRANSFORM_SKEWY, a b c dan d mewakili matriks yang akan menghasilkan skew yang diberikan (e=0 dan f=0). Untuk SVG_TRANSFORM_ROTATE, a b c d e dan f bersama-sama mewakili matriks yang akan menghasilkan rotasi yang diberikan. Ketika rotasi berada di sekitar titik pusat (0,0), e dan f akan menjadi nol."
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Matriks yang mewakili transformasi ini. Objek matriks bersifat langsung, yang berarti setiap perubahan yang dilakukan pada objek SVGTransform langsung tercermin pada objek matriks dan sebaliknya. Jika objek matriks diubah secara langsung (misalnya, tanpa menggunakan metode pada antarmuka SVGTransform itu sendiri), maka tipe SVGTransform berubah menjadi SVG_TRANSFORM_MATRIX. Untuk SVG_TRANSFORM_MATRIX, matriks berisi nilai a, b, c, d, e, f yang diberikan oleh pengguna. Untuk SVG_TRANSFORM_TRANSLATE, e dan f mewakili jumlah translasi (a=1, b=0, c=0, dan d=1). Untuk SVG_TRANSFORM_SCALE, a dan d mewakili jumlah skala (b=0, c=0, e=0, dan f=0). Untuk SVG_TRANSFORM_SKEWX dan SVG_TRANSFORM_SKEWY, a, b, c, dan d mewakili matriks yang akan menghasilkan skew yang diberikan (e=0 dan f=0). Untuk SVG_TRANSFORM_ROTATE, a, b, c, d, e, dan f bersama-sama mewakili matriks yang akan menghasilkan rotasi yang diberikan. Ketika rotasi berada di sekitar titik pusat (0,0), e dan f akan menjadi nol.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

Matriks yang mewakili transformasi ini.

### Lihat Juga

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
