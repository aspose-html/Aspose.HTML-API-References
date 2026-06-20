---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGLength 方法。保持相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因该方法而被修改。例如，如果原始值为 0.5cm 并且调用该方法将其转换为毫米，则 unitType 将更改为 SVG_LENGTHTYPE_MM，valueInSpecifiedUnits 将更改为数值 5，valueAsString 将更改为 5mm。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

保持相同的底层存储值，但将存储的单位标识符重置为给定的 unitType。对象属性 unitType、valueInSpecifiedUnits 和 valueAsString 可能会因该方法而被修改。例如，如果原始值为 "0.5cm" 并调用该方法转换为毫米，则 unitType 将更改为 SVG_LENGTHTYPE_MM，valueInSpecifiedUnits 将更改为数值 5，valueAsString 将更改为 "5mm"。

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 要切换到的单位类型（例如，SVG_LENGTHTYPE_MM）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)如果 unitType 为 SVG_LENGTHTYPE_UNKNOWN 或不是有效的单位类型常量（此接口上定义的其他 SVG_LENGTHTYPE_* 常量之一），则引发。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) 在长度对应只读属性或对象本身为只读时引发。 |

### 另请参见

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
