---
title: "SVGAngle 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle 类。SVGAngle 接口对应角度基本数据类型"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle 接口对应于 angle 基本数据类型。

```java
public class SVGAngle : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) 该值的类型由此接口上定义的 SVG_ANGLETYPE_* 常量之一指定。 |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | 保留相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因该方法而被修改。 |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | 将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值。 |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | 返回表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | 单位类型已明确设置为 degrees（度）。 |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | 单位类型为 radians（弧度）。 |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | 单位类型为 radians（弧度）。 |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | 单位类型不是预定义的单位类型之一。尝试定义此类型的新值或将现有值切换为此类型都是无效的。 |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | 未提供单位类型（即指定了无单位值）。对于角度，无单位值将被视为等同于指定了 degrees（度）。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
