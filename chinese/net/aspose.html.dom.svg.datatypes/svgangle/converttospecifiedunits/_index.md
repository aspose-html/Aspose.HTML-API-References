---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML for .NET API 参考
description: SVGAngle 方法. 保留相同的基础存储值但将存储的单元标识符重置为给定的 unitType对象属性 unitTypevalueInSpecifiedUnits 和 valueAsString 可能会由于此方法而被修改
type: docs
weight: 50
url: /zh/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

保留相同的基础存储值，但将存储的单元标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会由于此方法而被修改。

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 要切换到的单位类型（例如，SVG_ANGLETYPE_DEG）。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) 如果 unitType 是 SVG_ANGLETYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_ANGLETYPE_* 常量之一）则引发。 |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 当角度对应于只读属性或对象本身为只读时引发。 |

### 也可以看看

* class [SVGAngle](../)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* 部件 [Aspose.HTML](../../../)


