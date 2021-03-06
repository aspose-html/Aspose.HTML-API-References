---
title: ConvertToSpecifiedUnits
second_title: Aspose.HTML for .NET API 参考
description: 保留相同的底层存储值但将存储的单元标识符重置为给定的 unitType此方法可能会修改对象属性 unitTypevalueInSpecifiedUnits 和 valueAsString
type: docs
weight: 50
url: /zh/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

保留相同的底层存储值，但将存储的单元标识符重置为给定的 unitType。此方法可能会修改对象属性 unitType、valueInSpecifiedUnits 和 valueAsString。

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 要切换到的单位类型（例如，SVG_ANGLETYPE_DEG）。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | 代码NOT_SUPPORTED_ERR 如果 unitType 为 SVG_ANGLETYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_ANGLETYPE_* 常量之一），则引发。 |
| [DOMException](../../../aspose.html.dom/domexception) | 代码NO_MODIFICATION_ALLOWED_ERR 当角度对应于只读属性或对象本身为只读时引发。 |

### 也可以看看

* class [SVGAngle](../../svgangle)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../svgangle)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
