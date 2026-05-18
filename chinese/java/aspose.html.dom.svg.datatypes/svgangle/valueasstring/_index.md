---
title: "SVGAngle.ValueAsString"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGAngle 属性。角度值以 String 形式表示，单位由 unitType 指定。设置此属性将导致 value、valueInSpecifiedUnits 和 unitType 自动更新以反映此设置。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svgangle/valueasString/
---
## SVGAngle.ValueAsString property

角度值以 String 形式表示，单位由 unitType 指定。设置此属性将导致 value、valueInSpecifiedUnits 和 unitType 自动更新以反映此设置。

```java
public String ValueAsString { get; set; }
```

### Property Value

值为 String。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`SYNTAX_ERR`](../../../com.aspose.html.dom/domexception/syntax_err/) 在分配的 String 无法解析为有效角度时抛出。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) 在角度对应只读属性或对象本身为只读时抛出。 |

### 另请参阅

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
