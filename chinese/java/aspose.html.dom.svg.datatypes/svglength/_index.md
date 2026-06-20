---
title: "SVGLength 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.datatypes.SVGLength 类。SVGLength 接口对应长度基本数据类型。SVGLength 对象可以被指定为只读，这意味着尝试修改该对象将导致抛出如下所述的异常"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength 接口对应长度基本数据类型。SVGLength 对象可以被指定为只读，这意味着尝试修改该对象将导致抛出异常，如下所述。

```java
public class SVGLength : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) 该值的类型由此接口上定义的 SVG_LENGTHTYPE_* 常量之一指定。 |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | 保持相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因该方法而被修改。例如，如果原始值为 "0.5cm" 并调用该方法转换为毫米，则 unitType 将更改为 SVG_LENGTHTYPE_MM，valueInSpecifiedUnits 将更改为数值 5，valueAsString 将更改为 "5mm"。 |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | 将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值。 |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | 返回表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | 使用 CSS2 中定义的 cm 单位指定了一个值。 |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | 使用 CSS2 中定义的 em 单位指定了一个值。 |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | 使用 CSS2 中定义的 ex 单位指定了一个值。 |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | 使用 CSS2 中定义的 in 单位指定了一个值。 |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | 使用 CSS2 中定义的 mm 单位指定了一个值。 |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | 未提供单位类型（即指定了无单位值），这表示该值使用用户单位。 |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | 使用 CSS2 中定义的 pc 单位指定了一个值。 |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | 指定了百分比值。 |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | 使用 CSS2 中定义的 pt 单位指定了一个值。 |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | 使用 CSS2 中定义的 px 单位指定了一个值。 |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | 单位类型不属于预定义的单位类型。尝试定义此类型的新值或将现有值切换为此类型都是无效的。 |

### 另请参见

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
