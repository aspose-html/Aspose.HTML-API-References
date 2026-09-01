---
title: "Kelas SVGPathSeg"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg class. Antarmuka SVGPathSeg adalah antarmuka dasar yang sesuai dengan satu perintah dalam spesifikasi data jalur."
type: docs

url: /id/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

Antarmuka SVGPathSeg adalah antarmuka dasar yang sesuai dengan satu perintah dalam spesifikasi data path.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) Tipe segmen jalur sebagaimana ditentukan oleh salah satu konstanta yang didefinisikan pada antarmuka ini. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Tipe segmen jalur, ditentukan oleh nama perintah satu karakter yang sesuai. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Melepaskan sumber daya yang tidak terkelola dan - secara opsional - terkelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Mengacu pada perintah data jalur "absolute arcto" (A). |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Mengacu pada perintah data jalur "relative arcto" (a). |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Mengacu pada perintah data jalur "closepath" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Mengacu pada perintah data jalur "absolute cubic Bézier curveto" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Mengacu pada perintah data jalur "relative cubic Bézier curveto" (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Mengacu pada perintah data jalur "absolute smooth cubic curveto" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Mengacu pada perintah data jalur "relative smooth cubic curveto" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Mengacu pada perintah data jalur "absolute quadratic Bézier curveto" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Mengacu pada perintah data jalur "relative quadratic Bézier curveto" (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Mengacu pada perintah data jalur "absolute smooth quadratic curveto" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Mewakili perintah data jalur "relative smooth quadratic curveto" (t). |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Mewakili perintah data jalur "absolute lineto" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Mewakili perintah data jalur "absolute horizontal lineto" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Mewakili perintah data jalur "relative horizontal lineto" (h). |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Mewakili perintah data jalur "relative lineto" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Mewakili perintah data jalur "absolute vertical lineto" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Mewakili perintah data jalur "relative vertical lineto" (v). |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Mewakili perintah data jalur "absolute moveto" (M). |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Mewakili perintah data jalur "relative moveto" (m). |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Jenis unit bukan salah satu tipe yang telah ditentukan. Tidak valid mencoba mendefinisikan nilai baru dari tipe ini atau mencoba mengubah nilai yang ada ke tipe ini. |

### Lihat Juga

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
