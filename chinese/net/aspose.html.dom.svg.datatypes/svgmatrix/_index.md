---
title: Class SVGMatrix
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.DataTypes.SVGMatrix 班级. SVG 的许多图形操作使用以下形式的 2x3 矩阵 ace bdf 当为了矩阵运算的目的扩展为 3x3 矩阵时变为 ace bdf 0 0 1
type: docs
weight: 1220
url: /zh/net/aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

SVG 的许多图形操作使用以下形式的 2x3 矩阵： [ace] [bdf] 当为了矩阵运算的目的扩展为 3x3 矩阵时，变为： [ace] [bdf] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [A](../../aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | 矩阵的 A 分量。 |
| [B](../../aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | 矩阵的 B 分量。 |
| [C](../../aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | 矩阵的 C 分量。 |
| [D](../../aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | 矩阵的 D 分量。 |
| [E](../../aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | 矩阵的 E 分量。 |
| [F](../../aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | 矩阵的 F 分量。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管和 - 可选 - 托管资源。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [Multiply](../../aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | 执行矩阵乘法。该矩阵与另一个矩阵后乘，返回生成的新矩阵。 |
| [Rotate](../../aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | 在当前矩阵上后乘旋转变换并返回结果矩阵。 |
| [Scale](../../aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | 在当前矩阵上后乘一个统一比例变换并返回结果矩阵。 |
| [ScaleNonUniform](../../aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | 在当前矩阵上后乘非均匀缩放变换并返回结果矩阵。 |
| [SkewX](../../aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | 在当前矩阵上后乘一个 skewX 变换并返回结果矩阵。 |
| [SkewY](../../aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | 在当前矩阵上后乘一个 skewY 变换并返回结果矩阵。 |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgmatrix/tostring/)() | 返回一个String代表这个实例. |
| [Translate](../../aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | 在当前矩阵上后乘平移变换并返回结果矩阵。 |

### 也可以看看

* class [SVGValueType](../svgvaluetype/)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 部件 [Aspose.HTML](../../)


