---
title: "Clase SVGPathSeg"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg clase. La interfaz SVGPathSeg es una interfaz base que corresponde a un único comando dentro de una especificación de datos de ruta"
type: docs

url: /es/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

La interfaz SVGPathSeg es una interfaz base que corresponde a un único comando dentro de una especificación de datos de path.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) El tipo del segmento de ruta según lo especificado por una de las constantes definidas en esta interfaz. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) El tipo del segmento de ruta, especificado por el nombre del comando de un solo carácter correspondiente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Corresponde a un comando de datos de ruta "arcto absoluto" (A). |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Corresponde a un comando de datos de ruta "arcto relativo" (a). |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Corresponde a un comando de datos de ruta "closepath" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Corresponde a un comando de datos de ruta "curveto cúbico Bézier absoluto" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Corresponde a un comando de datos de ruta "curveto cúbico Bézier relativo" (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Corresponde a un comando de datos de ruta "curveto cúbico suave absoluto" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Corresponde a un comando de datos de ruta "curveto cúbico suave relativo" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Corresponde a un comando de datos de ruta "curveto cuadrático Bézier absoluto" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Corresponde a un comando de datos de ruta "curveto cuadrático Bézier relativo" (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Corresponde a un comando de datos de ruta "curveto cuadrático suave absoluto" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Corresponde a un "curveto cuadrático suave relativo" (t) comando de datos de ruta. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Corresponde a un "lineto absoluto" (L) comando de datos de ruta. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Corresponde a un "lineto horizontal absoluto" (H) comando de datos de ruta. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Corresponde a un "lineto horizontal relativo" (h) comando de datos de ruta. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Corresponde a un "lineto relativo" (l) comando de datos de ruta. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Corresponde a un "lineto vertical absoluto" (V) comando de datos de ruta. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Corresponde a un "lineto vertical relativo" (v) comando de datos de ruta. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Corresponde a un "moveto absoluto" (M) comando de datos de ruta. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Corresponde a un "moveto relativo" (m) comando de datos de ruta. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | El tipo de unidad no es uno de los tipos predefinidos. Es inválido intentar definir un nuevo valor de este tipo o intentar cambiar un valor existente a este tipo. |

### Ver también

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
