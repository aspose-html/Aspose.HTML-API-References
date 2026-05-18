---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGLength 方法。将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

将值重置为带有关联 unitType 的数字，从而替换对象上所有属性的值。

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unitType | UInt16 | 该值的单位类型。 |
| valueInSpecifiedUnits | 单精度浮点数 | 新值.. |

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) 在 unitType 为 SVG_LENGTHTYPE_UNKNOWN 或不是有效的单位类型常量时抛出（该接口上定义的其他 SVG_LENGTHTYPE_* 常量之一）。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) 在长度对应只读属性或对象本身为只读时引发。 |

### 另请参阅

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
