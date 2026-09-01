---
title: "ICSS2Properties.TextShadow"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性接受以逗号分隔的阴影效果列表，用于应用于元素的文本。阴影效果按照指定的顺序应用，可能会相互覆盖，但永不会覆盖文本本身。阴影效果不会改变盒子的大小，但可能会超出其边界。阴影效果的堆叠层级与元素本身相同。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

此属性接受以逗号分隔的阴影效果列表，用于应用于元素的文本。阴影效果按照指定的顺序应用，可能会相互覆盖，但永不会覆盖文本本身。阴影效果不会改变盒子的大小，但可能会超出其边界。阴影效果的[stack level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) 与元素本身相同。

每个阴影效果必须指定阴影偏移量，并可选地指定模糊半径和阴影颜色。

阴影偏移量使用两个'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' 值来指定，表示与文本的距离。第一个长度值指定文本右侧的水平距离。负的水平长度值会将阴影放置在文本左侧。第二个长度值指定文本下方的垂直距离。负的垂直长度值会将阴影放置在文本上方。

模糊半径可以在阴影偏移量之后可选地指定。模糊半径是一个长度值，表示模糊效果的边界。计算模糊效果的精确算法未指定。

可以在阴影效果的长度值之前或之后可选地指定颜色值。该颜色值将作为阴影效果的基础。如果未指定颜色，则会使用 ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) 属性的值。

```java
public String TextShadow { get; set; }
```

### 返回值

text-shadow 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
