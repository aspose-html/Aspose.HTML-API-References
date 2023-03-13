---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML for .NET API 参考
description: SVGLength 方法. 保留相同的基础存储值但将存储的单元标识符重置为给定的 unitType作为此方法的结果对象属性 unitTypevalueInSpecifiedUnits 和 valueAsString 可能会被修改例如原值为0.5cm调用方法转换为毫米则unitType改为SVG_LENGTHTYPE_MMvalueInSpecifiedUnits改为数值5valueAsString改为5mm
type: docs
weight: 50
url: /zh/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

保留相同的基础存储值，但将存储的单元标识符重置为给定的 unitType。作为此方法的结果，对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会被修改。例如，原值为“0.5cm”，调用方法转换为毫米，则unitType改为SVG_LENGTHTYPE_MM，valueInSpecifiedUnits改为数值5，valueAsString改为“5mm”。

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 要切换到的单位类型（例如，SVG_LENGTHTYPE_MM）。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) 如果 unitType 是 SVG_LENGTHTYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_LENGTHTYPE_* 常量之一）则引发。 |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 当长度对应于只读属性或对象本身为只读时引发。 |

### 也可以看看

* class [SVGLength](../)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* 部件 [Aspose.HTML](../../../)


