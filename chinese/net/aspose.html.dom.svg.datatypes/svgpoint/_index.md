---
title: Class SVGPoint
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.DataTypes.SVGPoint 班级. 许多 SVG DOM 接口都引用 SVGPoint 类的对象 SVGPoint 是 x y 坐标对当在矩阵运算中使用时SVGPoint 被视为以下形式的向量 x y 1 如果 SVGRect 对象被指定为只读则尝试分配给它的属性之一将导致抛出异常
type: docs
weight: 1250
url: /zh/net/aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

许多 SVG DOM 接口都引用 SVGPoint 类的对象。 SVGPoint 是 (x, y) 坐标对。当在矩阵运算中使用时，SVGPoint 被视为以下形式的向量： [x] [y] [1] 如果 SVGRect 对象被指定为只读，则尝试分配给它的属性之一将导致抛出异常。

```csharp
public class SVGPoint : SVGValueType
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [X](../../aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | X 坐标. |
| [Y](../../aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Y坐标. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管和 - 可选 - 托管资源。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [MatrixTransform](../../aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | 在此 SVGPoint 对象上应用 2x3 矩阵变换并返回一个新的、变换后的 SVGPoint 对象： newpoint = matrix* thispoint |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgpoint/tostring/)() | 返回一个String代表这个实例. |

### 也可以看看

* class [SVGValueType](../svgvaluetype/)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 部件 [Aspose.HTML](../../)


