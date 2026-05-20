---
title: "SVGPathSeg klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg klass. SVGPathSeg‑gränssnittet är ett basgränssnitt som motsvarar ett enskilt kommando inom en sökvägsdatabeskrivning."
type: docs

url: /sv/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg-gränssnittet är ett basgränssnitt som motsvarar ett enskilt kommando i en path-dataspecifikation.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) Typen av sökvägssegmentet enligt en av de konstanter som definieras på detta gränssnitt. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Typen av sökvägssegmentet, specificerad av motsvarande enkla tecken‑kommandonamn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Motsvarar ett "absolut arcto" (A) sökvägsdatakommandot. |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Motsvarar ett "relativt arcto" (a) sökvägsdatakommandot. |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Motsvarar ett "closepath" (z) sökvägsdatakommandot. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Motsvarar ett "absolut kubiskt Bézier curveto" (C) sökvägsdatakommandot. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Motsvarar ett "relativt kubiskt Bézier curveto" (c) sökvägsdatakommandet. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Motsvarar ett "absolut jämnt kubiskt curveto" (S) sökvägsdatakommandot. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Motsvarar ett "relativt jämnt kubiskt curveto" (s) sökvägsdatakommandot. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Motsvarar ett "absolut kvadratiskt Bézier curveto" (Q) sökvägsdatakommandot. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Motsvarar ett "relativt kvadratiskt Bézier curveto" (q) sökvägsdatakommandet. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Motsvarar ett "absolut jämnt kvadratiskt curveto" (T) sökvägsdatakommandot. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Motsvarar ett "relativt mjukt kvadratiskt curveto" (t) sökvägsdatakommandot. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Motsvarar ett "absolut lineto" (L) sökvägsdatakommandot. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Motsvarar ett "absolut horisontellt lineto" (H) sökvägsdatakommandot. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Motsvarar ett "relativt horisontellt lineto" (h) sökvägsdatakommandot. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Motsvarar ett "relativt lineto" (l) sökvägsdatakommandot. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Motsvarar ett "absolut vertikalt lineto" (V) sökvägsdatakommandot. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Motsvarar ett "relativt vertikalt lineto" (v) sökvägsdatakommandot. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Motsvarar ett "absolut moveto" (M) sökvägsdatakommandot. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Motsvarar ett "relativt moveto" (m) sökvägsdatakommandot. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Enhetstypen är inte en av de fördefinierade typerna. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka byta ett befintligt värde till denna typ. |

### Se även

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
