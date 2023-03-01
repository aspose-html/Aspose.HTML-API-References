---
title: Class SVGTransform
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform 班级. SVGTransform 是 SVGTransformList 中组件转换之一的接口因此SVGTransform 对象对应于transform属性规范中的单个组件例如scale或matrix
type: docs
weight: 1300
url: /zh/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform 是 SVGTransformList 中组件转换之一的接口；因此，SVGTransform 对象对应于“transform”属性规范中的单个组件（例如，“scale(…)”或“matrix(…)”）。

```csharp
public class SVGTransform : SVGValueType
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | SVG_TRANSFORM_ROTATE、SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY 的便利属性。它保存指定的角度。 对于 SVG_TRANSFORM_MATRIX、SVG_TRANSFORM_TRANSLATE 和 SVG_TRANSFORM_SCALE，角度将为零。 |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | 表示此转换的矩阵。矩阵对象是实时的，这意味着对 SVGTransform 对象所做的任何更改都会立即反映在矩阵对象中，反之亦然。如果直接更改矩阵对象（即不使用 SVGTransform 接口本身的方法），则 SVGTransform 的类型更改为 SVG_TRANSFORM_MATRIX. 对于 SVG_TRANSFORM_MATRIX，矩阵包含 a、b、c、d、e、f用户提供的值。 对于 SVG_TRANSFORM_TRANSLATE，e 和 f 表示平移量（a= 1，b= 0，c= 0 和 d = 1）。 对于 SVG_TRANSFORM_SCALE，a 和 d 表示缩放量（b= 0 , c= 0, e= 0 and f = 0). 对于 SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY，a、b、c 和 d 表示将导致给定偏斜的矩阵（e= 0 和 f = 0）。 对于 SVG_TRANSFORM_ROTATE , a, b, c, d, e 和 f 一起表示将导致给定旋转的矩阵。当旋转围绕中心点 (0, 0) 时，e 和 f 将为零。 |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | 此接口上定义的 SVG_TRANSFORM_* 常量之一指定的值类型。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管和 - 可选 - 托管资源。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | 将变换类型设置为 SVG_TRANSFORM_MATRIX，参数矩阵定义新的变换。复制参数矩阵的值，矩阵参数不会替换 SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | 将变换类型设置为 SVG_TRANSFORM_ROTATE，参数 angle 定义旋转角度，参数 cx 和 cy 定义可选的旋转中心。 |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | 将变换类型设置为 SVG_TRANSFORM_SCALE，参数 sx 和 sy 定义缩放量。 |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | 将变换类型设置为 SVG_TRANSFORM_SKEWX，参数角度定义倾斜量。 |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | 将变换类型设置为 SVG_TRANSFORM_SKEWY，参数角度定义倾斜量。 |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | 将转换类型设置为 SVG_TRANSFORM_TRANSLATE，参数 tx 和 ty 定义转换量。 |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | “矩阵（…）”转换。 |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | “旋转（...）”转换。 |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | “比例（...）”转换。 |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | 'skewX(…)' 转换。 |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | 'skewY(…)' 转换。 |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | “翻译（…）”转换。 |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | 单元类型不是预定义类型之一。尝试定义此类型的新值或尝试将现有值切换为此类型是无效的。 |

### 也可以看看

* class [SVGValueType](../svgvaluetype/)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 部件 [Aspose.HTML](../../)


