---
title: Class SVGTransform
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform kelas. SVGTransform adalah antarmuka untuk salah satu transformasi komponen dalam SVGTransformList dengan demikian objek SVGTransform sesuai dengan komponen tunggal misalnya skala atau matriks... dalam spesifikasi atribut transformasi.
type: docs
weight: 1300
url: /id/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform adalah antarmuka untuk salah satu transformasi komponen dalam SVGTransformList; dengan demikian, objek SVGTransform sesuai dengan komponen tunggal (misalnya, 'skala(…)' atau 'matriks(...)') dalam spesifikasi atribut 'transformasi'.

```csharp
public class SVGTransform : SVGValueType
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | Atribut praktis untuk SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX, dan SVG_TRANSFORM_SKEWY. Ini memegang sudut yang ditentukan. Untuk SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE dan SVG_TRANSFORM_SCALE, sudut akan menjadi nol. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | Matriks yang mewakili transformasi ini. Objek matriks hidup, artinya setiap perubahan yang dilakukan pada objek SVGTransform segera tercermin dalam objek matriks dan sebaliknya. Jika objek matriks diubah secara langsung (yaitu, tanpa menggunakan metode pada antarmuka SVGTransform itu sendiri) maka tipe SVGTransform berubah menjadi SVG_TRANSFORM_MATRIX. Untuk SVG_TRANSFORM_MATRIX, matriks berisi a, b, c, d, e, f nilai yang diberikan oleh pengguna. Untuk SVG_TRANSFORM_TRANSLATE, e dan f merepresentasikan besaran translasi(a= 1, b= 0, c= 0 dan d = 1). Untuk SVG_TRANSFORM_SCALE, a dan d merepresentasikan besaran skala(b= 0 , c= 0, e= 0 dan f = 0). Untuk SVG_TRANSFORM_SKEWX dan SVG_TRANSFORM_SKEWY, a, b, c dan d mewakili matriks yang akan menghasilkan kemiringan yang diberikan (e= 0 dan f = 0). Untuk SVG_TRANSFORM_ROTATE , a, b, c, d, e dan f bersama-sama mewakili matriks yang akan menghasilkan rotasi yang diberikan. Ketika rotasi berada di sekitar titik pusat (0, 0), e dan f akan menjadi nol. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | Jenis nilai seperti yang ditentukan oleh salah satu konstanta SVG_TRANSFORM_* yang ditentukan pada antarmuka ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Merilis sumber daya yang tidak dikelola dan - opsional - dikelola. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Menyetel tipe transformasi ke SVG_TRANSFORM_MATRIX, dengan matriks parameter yang menentukan transformasi baru. Nilai dari matriks parameter disalin, parameter matriks tidak menggantikan SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Mengatur tipe transformasi ke SVG_TRANSFORM_ROTATE, dengan parameter sudut menentukan sudut rotasi dan parameter cx dan cy menentukan pusat rotasi opsional. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Menyetel tipe transformasi ke SVG_TRANSFORM_SCALE, dengan parameter sx dan sy menentukan jumlah skala. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Menyetel tipe transformasi ke SVG_TRANSFORM_SKEWX, dengan sudut parameter menentukan jumlah kemiringan. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Menyetel tipe transformasi ke SVG_TRANSFORM_SKEWY, dengan sudut parameter menentukan jumlah kemiringan. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Menyetel tipe transformasi ke SVG_TRANSFORM_TRANSLATE, dengan parameter tx dan ty menentukan jumlah terjemahan. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Transformasi 'matriks(…)'. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Transformasi 'rotate(…)'. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Transformasi 'skala(…)'. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Transformasi 'skewX(…)'. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Transformasi 'skewY(…)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Transformasi 'terjemahkan(…)'. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Tipe unit bukan salah satu dari tipe yang telah ditentukan sebelumnya. Tidak valid mencoba menentukan nilai baru dari jenis ini atau mencoba mengalihkan nilai yang ada ke jenis ini. |

### Lihat juga

* class [SVGValueType](../svgvaluetype/)
* ruang nama [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* perakitan [Aspose.HTML](../../)


