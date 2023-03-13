---
title: SVGTransform.Matrix
second_title: Aspose.HTML for .NET API 参考
description: SVGTransform 财产. 表示此转换的矩阵矩阵对象是实时的这意味着对 SVGTransform 对象所做的任何更改都会立即反映在矩阵对象中反之亦然如果直接更改矩阵对象即不使用 SVGTransform 接口本身的方法则 SVGTransform 的类型更改为 SVG_TRANSFORM_MATRIX. 对于 SVG_TRANSFORM_MATRIX矩阵包含 abcdef用户提供的值 对于 SVG_TRANSFORM_TRANSLATEe 和 f 表示平移量a 1b 0c 0 和 d  1 对于 SVG_TRANSFORM_SCALEa 和 d 表示缩放量b 0  c 0 e 0 and f  0. 对于 SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWYabc 和 d 表示将导致给定偏斜的矩阵e 0 和 f  0 对于 SVG_TRANSFORM_ROTATE  a b c d e 和 f 一起表示将导致给定旋转的矩阵当旋转围绕中心点 0 0 时e 和 f 将为零
type: docs
weight: 20
url: /zh/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

表示此转换的矩阵。矩阵对象是实时的，这意味着对 SVGTransform 对象所做的任何更改都会立即反映在矩阵对象中，反之亦然。如果直接更改矩阵对象（即不使用 SVGTransform 接口本身的方法），则 SVGTransform 的类型更改为 SVG_TRANSFORM_MATRIX. 对于 SVG_TRANSFORM_MATRIX，矩阵包含 a、b、c、d、e、f用户提供的值。 对于 SVG_TRANSFORM_TRANSLATE，e 和 f 表示平移量（a= 1，b= 0，c= 0 和 d = 1）。 对于 SVG_TRANSFORM_SCALE，a 和 d 表示缩放量（b= 0 , c= 0, e= 0 and f = 0). 对于 SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY，a、b、c 和 d 表示将导致给定偏斜的矩阵（e= 0 和 f = 0）。 对于 SVG_TRANSFORM_ROTATE , a, b, c, d, e 和 f 一起表示将导致给定旋转的矩阵。当旋转围绕中心点 (0, 0) 时，e 和 f 将为零。

```csharp
public SVGMatrix Matrix { get; }
```

### 适当的价值

表示此转换的矩阵。

### 也可以看看

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* 部件 [Aspose.HTML](../../../)


