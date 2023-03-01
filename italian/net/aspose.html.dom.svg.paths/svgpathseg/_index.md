---
title: Class SVGPathSeg
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Svg.Paths.SVGPathSeg classe. Linterfaccia SVGPathSeg è uninterfaccia di base che corrisponde a un singolo comando allinterno di una specifica dei dati del percorso.
type: docs
weight: 1690
url: /it/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

L'interfaccia SVGPathSeg è un'interfaccia di base che corrisponde a un singolo comando all'interno di una specifica dei dati del percorso.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) { get; } | Il tipo di segmento del percorso come specificato da una delle costanti definite su questa interfaccia. |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | Il tipo di segmento di percorso, specificato dal corrispondente nome di comando di un carattere. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e, facoltativamente, gestite. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Corrisponde a un comando di dati di percorso "absolute arcto" (A). |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Corrisponde a un comando di dati di percorso "arco relativo" (a). |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Corrisponde a un comando di dati del percorso "closepath" (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Corrisponde a un comando di dati di percorso "absolute cubic Bézier curveto" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Corrisponde a un comando di dati di percorso "cubico relativo Bézier curveto" (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Corrisponde a un comando di dati di percorso "absolute smooth cubic curveto" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Corrisponde a un comando di dati di percorso "curva cubica uniforme relativa a" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Corrisponde a un comando di dati di percorso "assoluto quadratico Bézier curveto" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Corrisponde a un comando "curva Bézier quadratica relativa" (q) dei dati del percorso. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Corrisponde a un comando di dati di percorso "curva quadratica assoluta uniforme a" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Corrisponde a un comando di dati di percorso "curva quadratica uniforme relativa a" (t). |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Corrisponde a un comando di dati di percorso "absolute lineto" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Corrisponde a un comando di dati di percorso "linea orizzontale assoluta" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Corrisponde a un comando di dati di percorso "riga orizzontale relativa" (h). |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Corrisponde a un comando di dati di percorso "lineto relativo" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Corrisponde a un comando di dati di percorso "linea verticale assoluta" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Corrisponde a un comando di dati di percorso "linea verticale relativa" (v). |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Corrisponde a un comando di dati di percorso "absolute moveto" (M). |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Corrisponde a un comando di dati di percorso "spostamento relativo" (m). |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Il tipo di unità non è uno dei tipi predefiniti. Non è valido tentare di definire un nuovo valore di questo tipo o tentare di convertire un valore esistente in questo tipo. |

### Guarda anche

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* spazio dei nomi [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* assemblea [Aspose.HTML](../../)


