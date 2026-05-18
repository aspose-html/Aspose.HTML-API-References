---
title: "ICSS2Properties.Width"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性指定块级和替换元素生成的盒子的内容宽度。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

此属性指定块级和[替换](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element)元素生成的盒子的[内容宽度](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width)。

此属性不适用于非替换的 [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) 元素。非替换的内联元素的盒子的宽度等于其内部渲染内容的宽度（在子元素的任何相对偏移之前）。请记住，内联盒子会流入 [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box)。行盒子的宽度由它们的 [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) 决定，但可能会因 [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats) 的存在而被缩短。

替换元素的盒子的宽度是 [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic)，如果此属性的值不同于 'auto'，则可能会被用户代理按比例缩放。

以下值的含义如下：

‘[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)’ - 指定固定宽度。‘[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)’ - 指定百分比宽度。百分比是相对于生成盒子的 [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) 的宽度计算的。auto - 宽度取决于其他属性的值。请参阅下文各节。注意：['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) 的负值是非法的。

```java
public String Width { get; set; }
```

### 返回值

width 属性

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
