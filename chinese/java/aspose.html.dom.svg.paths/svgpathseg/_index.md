---
title: "SVGPathSeg 类。"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg 类。该 SVGPathSeg 接口是一个基础接口，对应于路径数据规范中的单个命令。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg 接口是一个基础接口，对应路径数据规范中的单个命令。

```java
public abstract class SVGPathSeg : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) 此路径段的类型，由此接口上定义的常量之一指定。 |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) 此路径段的类型，由相应的单字符命令名称指定。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | 对应于 “绝对弧线” (A) 路径数据命令。 |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | 对应于 “相对弧线” (a) 路径数据命令。 |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | 对应于 “闭合路径” (z) 路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | 对应于 “绝对三次贝塞尔曲线” (C) 路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | 对应于 “相对三次贝塞尔曲线” (c) 路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | 对应于 “绝对平滑三次曲线” (S) 路径数据命令。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | 对应于 “相对平滑三次曲线” (s) 路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | 对应于 “绝对二次贝塞尔曲线” (Q) 路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | 对应于 “相对二次贝塞尔曲线” (q) 路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | 对应于 “绝对平滑二次曲线” (T) 路径数据命令。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | 对应于 "relative smooth quadratic curveto" (t) 路径数据命令。 |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | 对应于 "absolute lineto" (L) 路径数据命令。 |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | 对应于 " absolute horizontal lineto" (H) 路径数据命令。 |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | 对应于 "relative horizontal lineto" (h) 路径数据命令。 |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | 对应于 "relative lineto" (l) 路径数据命令。 |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | 对应于 "absolute vertical lineto" (V) 路径数据命令。 |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | 对应于 "relative vertical lineto" (v) 路径数据命令。 |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | 对应于 "absolute moveto" (M) 路径数据命令。 |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | 对应于 "relative moveto" (m) 路径数据命令。 |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | 单位类型不是预定义类型之一。尝试定义此类型的新值或尝试将现有值切换到此类型都是无效的。 |

### 另请参见

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
