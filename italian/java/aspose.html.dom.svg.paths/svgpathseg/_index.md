---
title: "Classe SVGPathSeg"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.dom.svg.paths.SVGPathSeg. L'interfaccia SVGPathSeg è un'interfaccia base che corrisponde a un singolo comando all'interno di una specifica di dati di percorso"
type: docs

url: /it/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

L'interfaccia SVGPathSeg è un'interfaccia base che corrisponde a un singolo comando all'interno di una specifica di dati di percorso.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) Il tipo del segmento di percorso come specificato da una delle costanti definite su questa interfaccia. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Il tipo del segmento di percorso, specificato dal corrispondente nome di comando a un carattere. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Corrisponde a un comando di dati di percorso "arcto assoluto" (A). |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Corrisponde a un comando di dati di percorso "arcto relativo" (a). |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Corrisponde a un comando di dati di percorso "closepath" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Corrisponde a un comando di dati di percorso "curveto Bézier cubico assoluto" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Corrisponde a un comando di dati di percorso "curveto Bézier cubico relativo" (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Corrisponde a un comando di dati di percorso "curveto cubico liscio assoluto" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Corrisponde a un comando di dati di percorso "curveto cubico liscio relativo" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Corrisponde a un comando di dati di percorso "curveto Bézier quadratico assoluto" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Corrisponde a un comando di dati di percorso "curveto Bézier quadratico relativo" (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Corrisponde a un comando di dati di percorso "curveto quadratico liscio assoluto" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Corrisponde a un "relative smooth quadratic curveto" (t) comando di dati del percorso. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Corrisponde a un "absolute lineto" (L) comando di dati del percorso. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Corrisponde a un " absolute horizontal lineto" (H) comando di dati del percorso. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Corrisponde a un "relative horizontal lineto" (h) comando di dati del percorso. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Corrisponde a un "relative lineto" (l) comando di dati del percorso. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Corrisponde a un " absolute vertical lineto" (V) comando di dati del percorso. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Corrisponde a un "relative vertical lineto" (v) comando di dati del percorso. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Corrisponde a un "absolute moveto" (M) comando di dati del percorso. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Corrisponde a un "relative moveto" (m) comando di dati del percorso. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Il tipo di unità non è uno dei tipi predefiniti. È invalido tentare di definire un nuovo valore di questo tipo o di tentare di cambiare un valore esistente a questo tipo. |

### Vedi anche

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
