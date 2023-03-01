---
title: Class SVGAngle
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.DataTypes.SVGAngle 班级. SVGAngle接口对应角度基本数据类型.
type: docs
weight: 1060
url: /zh/net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle接口对应角度基本数据类型.

```csharp
public class SVGAngle : SVGValueType
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svgangle/unittype/) { get; } | 此接口上定义的 SVG_ANGLETYPE_* 常量之一指定的值类型。 |
| [Value](../../aspose.html.dom.svg.datatypes/svgangle/value/) { get; set; } | 作为浮点值的角度值，以度为单位。设置此属性将导致 valueInSpecifiedUnits 和 valueAsString 自动更新以反映此设置。 |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svgangle/valueasstring/) { get; set; } | 作为字符串值的角度值，单位由 unitType 表示。设置此属性将导致值、valueInSpecifiedUnits 和 unitType 自动更新以反映此设置。 |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | 作为浮点值的角度值，单位由 unitType 表示。设置此属性将导致 value 和 valueAsString 自动更新以反映此设置。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | 保留相同的基础存储值，但将存储的单元标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会由于此方法而被修改。 |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管和 - 可选 - 托管资源。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | 将值重置为具有关联 unitType 的数字，从而替换对象上所有属性的值。 |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgangle/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | 单位类型明确设置为度数。 |
| const [SVG_ANGLETYPE_GRAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | 单位类型为弧度。 |
| const [SVG_ANGLETYPE_RAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | 单位类型为弧度。 |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | 单元类型不是预定义单元类型之一。尝试定义此类型的新值或尝试将现有值切换为此类型是无效的。 |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | 未提供单位类型（即，指定了无单位值）。对于角度，无单位值的处理方式与指定的度数相同。 |

### 也可以看看

* class [SVGValueType](../svgvaluetype/)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 部件 [Aspose.HTML](../../)


