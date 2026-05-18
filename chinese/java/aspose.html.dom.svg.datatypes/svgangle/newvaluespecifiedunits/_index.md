---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGAngle 方法。将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值。

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newUnitType | UInt16 | 值的单位类型（例如，SVG_ANGLETYPE_DEG）。 |
| valueInSpecifiedUnits | 单精度浮点数 | 角度值。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) 在 unitType 为 SVG_ANGLETYPE_UNKNOWN 或不是有效的单位类型常量时抛出（该接口上定义的其他 SVG_ANGLETYPE_* 常量之一）。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) 在角度对应只读属性或对象本身为只读时抛出。 |

### 另请参阅

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
