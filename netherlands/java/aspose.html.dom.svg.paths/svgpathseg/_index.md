---
title: "SVGPathSeg Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg klasse. De SVGPathSeg interface is een basisinterface die overeenkomt met een enkel commando binnen een padgegevensspecificatie"
type: docs

url: /nl/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

De SVGPathSeg-interface is een basisinterface die overeenkomt met een enkel commando binnen een pad-dataspecificatie.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) Het type van het padsegment zoals gespecificeerd door een van de constanten die op deze interface zijn gedefinieerd. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Het type van het padsegment, gespecificeerd door de overeenkomstige één‑karakter‑opdrachtnaam. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft onbeheerste en - optioneel - beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Komt overeen met een "absolute arcto" (A) padgegevenscommando. |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Komt overeen met een "relatieve arcto" (a) padgegevenscommando. |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Komt overeen met een "closepath" (z) padgegevenscommando. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Komt overeen met een "absolute kubieke Bézier curveto" (C) padgegevenscommando. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Komt overeen met een "relatieve kubieke Bézier curveto" (c) padgegevenscommando. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Komt overeen met een "absolute gladde kubieke curveto" (S) padgegevenscommando. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Komt overeen met een "relatieve gladde kubieke curveto" (s) padgegevenscommando. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Komt overeen met een "absolute kwadratische Bézier curveto" (Q) padgegevenscommando. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Komt overeen met een "relatieve kwadratische Bézier curveto" (q) padgegevenscommando. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Komt overeen met een "absolute gladde kwadratische curveto" (T) padgegevenscommando. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Komt overeen met een "relative smooth quadratic curveto" (t) padgegevenscommando. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Komt overeen met een "absolute lineto" (L) padgegevenscommando. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Komt overeen met een " absolute horizontal lineto" (H) padgegevenscommando. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Komt overeen met een "relative horizontal lineto" (h) padgegevenscommando. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Komt overeen met een "relative lineto" (l) padgegevenscommando. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Komt overeen met een " absolute vertical lineto" (V) padgegevenscommando. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Komt overeen met een "relative vertical lineto" (v) padgegevenscommando. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Komt overeen met een "absolute moveto" (M) padgegevenscommando. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Komt overeen met een "relative moveto" (m) padgegevenscommando. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Het eenheidstype is niet een van de vooraf gedefinieerde typen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om te proberen een bestaande waarde naar dit type te wijzigen. |

### Zie ook

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
