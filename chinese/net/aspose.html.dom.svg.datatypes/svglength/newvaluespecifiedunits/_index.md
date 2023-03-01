---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.HTML for .NET API 参考
description: SVGLength 方法. 将值重置为具有关联 unitType 的数字从而替换对象上所有属性的值
type: docs
weight: 60
url: /zh/net/aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

将值重置为具有关联 unitType 的数字，从而替换对象上所有属性的值。

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 值的单位类型。 |
| valueInSpecifiedUnits | Single | 新价值.. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) 如果 unitType 是 SVG_LENGTHTYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_LENGTHTYPE_* 常量之一）则引发。 |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 当长度对应于只读属性或对象本身为只读时引发。 |

### 也可以看看

* class [SVGLength](../)
* 命名空间 [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* 部件 [Aspose.HTML](../../../)


