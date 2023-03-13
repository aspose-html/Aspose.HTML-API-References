---
title: Class SVGLength
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength 班级. SVGLength 接口对应长度基本数据类型 SVGLength 对象可以指定为只读这意味着尝试修改该对象将导致抛出异常如下所述
type: docs
weight: 1200
url: /zh/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength 接口对应长度基本数据类型。 SVGLength 对象可以指定为只读，这意味着尝试修改该对象将导致抛出异常，如下所述。

```csharp
public class SVGLength : SVGValueType
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | 此接口上定义的 SVG_LENGTHTYPE_* 常量之一指定的值类型。 |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | 该值作为浮点值，以用户单位表示。设置此属性将导致 valueInSpecifiedUnits 和 valueAsString 自动更新以反映此设置。 |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | 作为字符串值的值，单位由 unitType 表示。设置此属性将导致值、valueInSpecifiedUnits 和 unitType 自动更新以反映此设置。 |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | 作为浮点值的值，单位由 unitType 表示。设置此属性将导致 value 和 valueAsString 自动更新以反映此设置。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | 保留相同的基础存储值，但将存储的单元标识符重置为给定的 unitType。作为此方法的结果，对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会被修改。例如，原值为“0.5cm”，调用方法转换为毫米，则unitType改为SVG_LENGTHTYPE_MM，valueInSpecifiedUnits改为数值5，valueAsString改为“5mm”。 |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管和 - 可选 - 托管资源。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | 将值重置为具有关联 unitType 的数字，从而替换对象上所有属性的值。 |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | 使用 CSS2. 中定义的厘米单位指定值 |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | 使用 CSS2. 中定义的 em 单位指定了一个值 |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | 使用 CSS2. 中定义的 ex 单位指定了一个值 |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | 使用 CSS2. 中定义的单位指定值 |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | 使用 CSS2. 中定义的毫米单位指定值 |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | 未提供单位类型（即指定了无单位值），表示以用户单位表示的值。 |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | 使用 CSS2. 中定义的 pc 单位指定值 |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | 指定了百分比值。 |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | 使用 CSS2. 中定义的 pt 单位指定了一个值 |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | 使用 CSS2. 中定义的 px 单位指定值 |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | 单元类型不是预定义单元类型之一。尝试定义此类型的新值或尝试将现有值切换为此类型是无效的。 |

### 也可以看看

* class [SVGValueType](../svgvaluetype/)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 部件 [Aspose.HTML](../../)


