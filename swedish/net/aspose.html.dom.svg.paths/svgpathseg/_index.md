---
title: Class SVGPathSeg
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Svg.Paths.SVGPathSeg klass. SVGPathSeggränssnittet är ett basgränssnitt som motsvarar ett enda kommando inom en sökvägsdataspecifikation.
type: docs
weight: 1690
url: /sv/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg-gränssnittet är ett basgränssnitt som motsvarar ett enda kommando inom en sökvägsdataspecifikation.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) { get; } | Typen av sökvägssegmentet som specificeras av en av konstanterna som definieras i detta gränssnitt. |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | Typen av sökvägssegmentet, specificerad av motsvarande ett teckens kommandonamn. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Motsvarar ett "absolute arcto" (A) sökvägsdatakommando. |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Motsvarar ett "relativ arcto" (a) sökvägsdatakommando. |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Motsvarar ett "closepath" (z) sökvägsdatakommando. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Motsvarar ett "absolut kubisk Bézier curveto" (C) sökvägsdatakommando. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Motsvarar ett "relativ kubisk Bézier curveto" (c) sökvägsdatakommando. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Motsvarar ett "absolut smooth cubic curveto" (S) sökvägsdatakommando. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Motsvarar ett "relativ jämn kubisk kurva" (s) sökvägsdatakommando. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Motsvarar ett "absolut kvadratisk Bézier curveto" (Q) sökvägsdatakommando. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Motsvarar ett "relativ kvadratisk Bézier curveto" (q) sökvägsdatakommando. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Motsvarar ett "absolut jämn kvadratisk kurva" (T) vägdatakommando. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Motsvarar ett "relativ jämn kvadratisk kurva" (t) sökvägsdatakommando. |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Motsvarar ett "absolut lineto" (L) sökvägsdatakommando. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Motsvarar ett "absolut horisontell linje till" (H) sökvägsdatakommando. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Motsvarar ett "relativ horisontell linje till" (h) sökvägsdatakommando. |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Motsvarar ett "relativ lineto" (l) sökvägsdatakommando. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Motsvarar ett "absolut vertikal lineto" (V) sökvägsdatakommando. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Motsvarar ett "relativ vertikal linjeto" (v) sökvägsdatakommando. |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Motsvarar ett "absolute moveto" (M) sökvägsdatakommando. |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Motsvarar ett "relativ moveto" (m) sökvägsdatakommando. |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Enhetstypen är inte en av fördefinierade typer. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka ändra ett befintligt värde till denna typ. |

### Se även

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* namnutrymme [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* hopsättning [Aspose.HTML](../../)


