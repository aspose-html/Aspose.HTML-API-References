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
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Tipe segmen jalur, ditentukan oleh nama perintah satu karakter yang bersesuaian. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Melepaskan sumber daya yang tidak terkelola dan - secara opsional - terkelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Berhubungan dengan perintah data jalur \"arcto absolut\" (A). |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Berhubungan dengan perintah data jalur \"arcto relatif\" (a). |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Berhubungan dengan perintah data jalur \"closepath\" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Berhubungan dengan perintah data jalur \"Bézier kubik absolut\" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Berhubungan dengan perintah data jalur \"Bézier kubik relatif\" (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Berhubungan dengan perintah data jalur \"kubik halus absolut\" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Berhubungan dengan perintah data jalur \"kubik halus relatif\" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Berhubungan dengan perintah data jalur \"Bézier kuadratik absolut\" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Berhubungan dengan perintah data jalur \"Bézier kuadratik relatif\" (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Berhubungan dengan perintah data jalur \"kuadratik halus absolut\" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Mengacu pada perintah data jalur "relative smooth quadratic curveto" (t). |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Mengacu pada perintah data jalur "absolute lineto" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Mengacu pada perintah data jalur "absolute horizontal lineto" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Mengacu pada perintah data jalur "relative horizontal lineto" (h). |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Mengacu pada perintah data jalur "relative lineto" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Mengacu pada perintah data jalur "absolute vertical lineto" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Mengacu pada perintah data jalur "relative vertical lineto" (v). |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Mengacu pada perintah data jalur "absolute moveto" (M). |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Mengacu pada perintah data jalur "relative moveto" (m). |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Jenis unit bukan salah satu tipe yang telah ditentukan. Tidak valid mencoba mendefinisikan nilai baru untuk tipe ini atau mencoba mengubah nilai yang ada ke tipe ini. |

### Lihat Juga

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
