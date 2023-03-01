---
title: Class SVGPathSeg
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Svg.Paths.SVGPathSeg klas. Die SVGPathSegSchnittstelle ist eine Basisschnittstelle die einem einzelnen Befehl innerhalb einer Pfaddatenspezifikation entspricht.
type: docs
weight: 1690
url: /de/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

Die SVGPathSeg-Schnittstelle ist eine Basisschnittstelle, die einem einzelnen Befehl innerhalb einer Pfaddatenspezifikation entspricht.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) { get; } | Der Typ des Pfadsegments, wie er durch eine der auf dieser Schnittstelle definierten Konstanten angegeben wird. |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | Der Typ des Pfadsegments, angegeben durch den entsprechenden einstelligen Befehlsnamen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Entspricht einem "absolute arcto" (A) Bahndatenbefehl. |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Entspricht einem "relative arcto" (a) Pfaddatenbefehl. |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Entspricht einem Pfaddatenbefehl „closepath“ (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Entspricht einem Pfaddatenbefehl "absolute kubische Bézier-Kurve" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Entspricht einem Pfaddatenbefehl „relative kubische Bézier-Kurve“ (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Entspricht einem Bahndatenbefehl „absolute glatte kubische Kurve“ (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Entspricht einem Pfaddatenbefehl "relative glatte kubische Kurve zu" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Entspricht einem Pfaddatenbefehl "absolute quadratische Bézier-Kurve" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Entspricht einem Pfaddatenbefehl „relative quadratische Bézier-Kurve“ (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Entspricht einem Pfaddatenbefehl "absolute glatte quadratische Kurve" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Entspricht einem Pfaddatenbefehl "relative glatte quadratische Kurve zu" (t). |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Entspricht einem Pfaddatenbefehl "absolute lineto" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Entspricht einem "absolute horizontal lineto" (H) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Entspricht einem "relative horizontal lineto" (h) Pfaddatenbefehl. |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Entspricht einem Pfaddatenbefehl „relative lineto“ (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Entspricht einem Pfaddatenbefehl "absolute vertikale Linie zu" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Entspricht einem "relative vertical lineto" (v) Pfaddatenbefehl. |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Entspricht einem Bahndatenbefehl "absolute moveto" (M). |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Entspricht einem "relative moveto" (m) Pfaddatenbefehl. |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Der Einheitentyp ist keiner der vordefinierten Typen. Es ist ungültig, einen neuen Wert dieses Typs zu definieren oder einen vorhandenen Wert auf diesen Typ umzustellen. |

### Siehe auch

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* namensraum [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* Montage [Aspose.HTML](../../)


