---
title: SVGPathSeg
second_title: Aspose.HTML for .NET API 参考
description: SVGPathSeg 接口是一个基本接口对应于路径数据规范中的单个命令
type: docs
weight: 1800
url: /zh/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg 接口是一个基本接口，对应于路径数据规范中的单个命令。

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype) { get; } | 路径段的类型，由此接口上定义的常量之一指定。 |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter) { get; } | 路径段的类型，由对应的单字符命令名指定。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose)() | 释放非托管和 - 可选 - 托管资源。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | 此方法用于检索 ECMAScript 对象Type。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs) | 对应于“absolute arcto”（A）路径数据命令。 |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel) | 对应于“相对 arcto”（a）路径数据命令。 |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath) | 对应于“closepath”（z）路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs) | 对应于“绝对三次贝塞尔曲线”（C）路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel) | 对应于“相对三次贝塞尔曲线”（c）路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs) | 对应于“绝对平滑三次曲线”（S）路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel) | 对应于“相对平滑三次曲线”（s）路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs) | 对应于“绝对二次贝塞尔曲线”（Q）路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel) | 对应于“相对二次贝塞尔曲线”（q）路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs) | 对应于“绝对平滑二次曲线到”（T）路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel) | 对应于“相对平滑二次曲线”（t）路径数据命令。 |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs) | 对应于“absolute lineto”（L）路径数据命令。 |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs) | 对应于“绝对水平线到”（H）路径数据命令。 |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel) | 对应于“相对水平线到”（h）路径数据命令。 |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel) | 对应于“relative lineto”（l）路径数据命令。 |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs) | 对应于“绝对垂直线到”（V）路径数据命令。 |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel) | 对应于“相对垂直线”（v）路径数据命令。 |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs) | 对应于“绝对移动到”（M）路径数据命令。 |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel) | 对应于“相对移动”（m）路径数据命令。 |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown) | 单位类型不是预定义类型之一。尝试定义此类型的新值或尝试将现有值切换到此类型是无效的。 |

### 也可以看看

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype)
* 命名空间 [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->