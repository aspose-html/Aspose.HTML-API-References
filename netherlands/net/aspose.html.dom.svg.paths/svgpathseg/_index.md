---
title: Class SVGPathSeg
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Svg.Paths.SVGPathSeg klas. De SVGPathSeginterface is een basisinterface die overeenkomt met een enkele opdracht binnen een padgegevensspecificatie.
type: docs
weight: 1690
url: /nl/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

De SVGPathSeg-interface is een basisinterface die overeenkomt met een enkele opdracht binnen een padgegevensspecificatie.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) { get; } | Het type padsegment zoals gespecificeerd door een van de constanten die op deze interface zijn gedefinieerd. |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | Het type padsegment, gespecificeerd door de overeenkomstige opdrachtnaam van één teken. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Geeft onbeheerde en - optioneel - beheerde bronnen vrij. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Komt overeen met een "absolute arcto" (A) padgegevensopdracht. |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Komt overeen met een opdracht "relatieve arcto" (a) padgegevens. |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Komt overeen met een "closepath" (z) padgegevenscommando. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Komt overeen met een "absolute kubieke Bézier-curvenaar" (C) padgegevenscommando. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Komt overeen met een "relatieve kubieke Bézier-curvenaar" (c) padgegevenscommando. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Komt overeen met een "absolute vloeiende kubische kromme naar" (S) padgegevenscommando. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Komt overeen met een "relatief vloeiende kubieke curve naar" (s) padgegevenscommando. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Komt overeen met een "absolute kwadratische Bézier-curvenaar" (Q) padgegevenscommando. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Komt overeen met een "relatieve kwadratische Bézier-curvenaar" (q) padgegevenscommando. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Komt overeen met een "absolute vloeiende kwadratische curve naar" (T) padgegevenscommando. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Komt overeen met een "relatief vloeiende kwadratische curve naar" (t) padgegevenscommando. |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Komt overeen met een opdracht "absolute lineto" (L) padgegevens. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Komt overeen met een opdracht "absolute horizontale lijn naar" (H) padgegevens. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Komt overeen met een opdracht "relatieve horizontale lijn naar" (h) padgegevens. |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Komt overeen met een opdracht "relatieve lijn naar" (l) padgegevens. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Komt overeen met een opdracht "absolute verticale lijn naar" (V) padgegevens. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Komt overeen met een opdracht "relatieve verticale lijn naar" (v) padgegevens. |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Komt overeen met een opdracht "absolute verplaatsing naar" (M) padgegevens. |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Komt overeen met een opdracht "relatieve verplaatsing naar" (m) padgegevens. |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Het eenheidstype is niet een van de vooraf gedefinieerde typen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om een bestaande waarde naar dit type om te schakelen. |

### Zie ook

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* naamruimte [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* montage [Aspose.HTML](../../)


