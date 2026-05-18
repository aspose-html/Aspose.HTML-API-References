---
title: "SVGPathSeg Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg Klasse. Das SVGPathSeg Interface ist ein Basis-Interface, das einem einzelnen Befehl innerhalb einer Pfaddaten-Spezifikation entspricht."
type: docs

url: /de/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

Die SVGPathSeg‑Schnittstelle ist eine Basisschnittstelle, die einem einzelnen Befehl innerhalb einer Pfaddaten‑Spezifikation entspricht.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) Der Typ des Pfadsegments, wie durch eine der auf diesem Interface definierten Konstanten angegeben. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Der Typ des Pfadsegments, angegeben durch den entsprechenden einzeichenbefehl. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und - optional - verwaltete Ressourcen frei. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Entspricht einem "absoluten arcto" (A) Pfaddatenbefehl. |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Entspricht einem "relativen arcto" (a) Pfaddatenbefehl. |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Entspricht einem "closepath" (z) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Entspricht einem "absoluten kubischen Bézier Curveto" (C) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Entspricht einem "relativen kubischen Bézier Curveto" (c) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Entspricht einem "absoluten glatten kubischen Curveto" (S) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Entspricht einem "relativen glatten kubischen Curveto" (s) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Entspricht einem "absoluten quadratischen Bézier Curveto" (Q) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Entspricht einem "relativen quadratischen Bézier Curveto" (q) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Entspricht einem "absoluten glatten quadratischen Curveto" (T) Pfaddatenbefehl. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Entspricht einem "relativen sanften quadratischen Kurvenbefehl" (t) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Entspricht einem "absoluten lineto" (L) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Entspricht einem "absoluten horizontalen lineto" (H) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Entspricht einem "relativen horizontalen lineto" (h) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Entspricht einem "relativen lineto" (l) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Entspricht einem "absoluten vertikalen lineto" (V) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Entspricht einem "relativen vertikalen lineto" (v) Pfaddatenbefehl. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Entspricht einem "absoluten moveto" (M) Pfaddatenbefehl. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Entspricht einem "relativen moveto" (m) Pfaddatenbefehl. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Der Einheitstyp ist keiner der vordefinierten Typen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |

### Siehe auch

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
