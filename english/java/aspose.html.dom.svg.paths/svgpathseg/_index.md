---
title: SVGPathSeg Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Svg.Paths.SVGPathSeg class. The SVGPathSeg interface is a base interface that corresponds to a single command within a path data specification
type: docs
weight: 1700
url: /java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

The SVGPathSeg interface is a base interface that corresponds to a single command within a path data specification.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Properties

| Name | Description |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) The type of the path segment as specified by one of the constants defined on this interface. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) The type of the path segment, specified by the corresponding one character command name. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |

## Fields

| Name | Description |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Corresponds to a "absolute arcto" (A) path data command. |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Corresponds to a "relative arcto" (a) path data command. |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Corresponds to a "closepath" (z) path data command. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Corresponds to a "absolute cubic Bézier curveto" (C) path data command. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Corresponds to a "relative cubic Bézier curveto" (c) path data command. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Corresponds to a "absolute smooth cubic curveto" (S) path data command. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Corresponds to a "relative smooth cubic curveto" (s) path data command. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Corresponds to a "absolute quadratic Bézier curveto" (Q) path data command. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Corresponds to a "relative quadratic Bézier curveto" (q) path data command. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Corresponds to a "absolute smooth quadratic curveto" (T) path data command. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Corresponds to a "relative smooth quadratic curveto" (t) path data command. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Corresponds to a "absolute lineto" (L) path data command. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Corresponds to a "absolute horizontal lineto" (H) path data command. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Corresponds to a "relative horizontal lineto" (h) path data command. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Corresponds to a "relative lineto" (l) path data command. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Corresponds to a "absolute vertical lineto" (V) path data command. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Corresponds to a "relative vertical lineto" (v) path data command. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Corresponds to a "absolute moveto" (M) path data command. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Corresponds to a "relative moveto" (m) path data command. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | The unit type is not one of predefined types. It is invalid to attempt to define a new value of this type or to attempt to switch an existing value to this type. |

### See Also

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.Dom.Svg.Paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
