---
title: "Kelas SVGTransform"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.dom.svg.datatypes.SVGTransform. SVGTransform adalah antarmuka untuk salah satu transformasi komponen dalam SVGTransformList sehingga objek SVGTransform sesuai dengan satu komponen, misalnya skala atau matriks dalam spesifikasi atribut transform"
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform adalah antarmuka untuk salah satu transformasi komponen dalam SVGTransformList; sehingga, objek SVGTransform sesuai dengan satu komponen tunggal (misalnya, 'scale(…)' atau 'matrix(…)') dalam spesifikasi atribut ‘transform’.

```java
public class SVGTransform : SVGValueType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Atribut kemudahan untuk SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX, dan SVG_TRANSFORM_SKEWY. Ini menyimpan sudut yang ditentukan. Untuk SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE, dan SVG_TRANSFORM_SCALE, sudut akan menjadi nol. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) Matriks yang merepresentasikan transformasi ini. Objek matriks bersifat hidup, artinya setiap perubahan yang dilakukan pada objek SVGTransform langsung tercermin pada objek matriks dan sebaliknya. Jika objek matriks diubah secara langsung (misalnya, tanpa menggunakan metode pada antarmuka SVGTransform itu sendiri) maka tipe SVGTransform berubah menjadi SVG_TRANSFORM_MATRIX. Untuk SVG_TRANSFORM_MATRIX, matriks berisi nilai a, b, c, d, e, f yang diberikan oleh pengguna. Untuk SVG_TRANSFORM_TRANSLATE, e dan f mewakili nilai translasi (a=1, b=0, c=0, d=1). Untuk SVG_TRANSFORM_SCALE, a dan d mewakili nilai skala (b=0, c=0, e=0, f=0). Untuk SVG_TRANSFORM_SKEWX dan SVG_TRANSFORM_SKEWY, a, b, c, dan d mewakili matriks yang menghasilkan skew yang diberikan (e=0 dan f=0). Untuk SVG_TRANSFORM_ROTATE, a, b, c, d, e, dan f bersama-sama mewakili matriks yang menghasilkan rotasi yang diberikan. Ketika rotasi berada di sekitar titik pusat (0, 0), e dan f akan menjadi nol. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) Tipe nilai sebagaimana ditentukan oleh salah satu konstanta SVG_TRANSFORM_* yang didefinisikan pada antarmuka ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Melepaskan sumber daya yang tidak terkelola dan - secara opsional - terkelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Mengatur tipe transformasi menjadi SVG_TRANSFORM_MATRIX, dengan parameter matrix yang mendefinisikan transformasi baru. Nilai-nilai dari parameter matrix disalin, parameter matrix tidak menggantikan SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Mengatur tipe transformasi menjadi SVG_TRANSFORM_ROTATE, dengan parameter angle yang menentukan sudut rotasi dan parameter cx serta cy yang menentukan pusat rotasi opsional. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Mengatur tipe transformasi menjadi SVG_TRANSFORM_SCALE, dengan parameter sx dan sy yang menentukan nilai skala. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Mengatur tipe transformasi menjadi SVG_TRANSFORM_SKEWX, dengan parameter angle yang menentukan besaran skew. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Mengatur tipe transformasi menjadi SVG_TRANSFORM_SKEWY, dengan parameter angle yang menentukan besaran skew. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Mengatur tipe transformasi menjadi SVG_TRANSFORM_TRANSLATE, dengan parameter tx dan ty yang menentukan nilai translasi. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Transformasi 'matrix(…)'. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Transformasi 'rotate(…)'. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Sebuah transformasi 'scale(…)' |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Sebuah transformasi 'skewX(…)' |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Sebuah transformasi 'skewY(…)' |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Sebuah transformasi 'translate(…)' |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Jenis unit bukan salah satu tipe yang telah ditentukan. Tidak valid mencoba mendefinisikan nilai baru untuk tipe ini atau mencoba mengubah nilai yang ada ke tipe ini. |

### Lihat Juga

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
