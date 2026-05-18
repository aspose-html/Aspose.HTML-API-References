---
title: "此属性的取值含义如下："
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。使用 outline 属性创建的轮廓绘制在盒子之上，即轮廓始终位于顶部，并且不影响盒子或其他任何盒子的定位或尺寸。因此，显示或隐藏轮廓不会导致重排。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/outlinecolor/
---
## ICSS2Properties.OutlineColor property

使用 outline 属性创建的轮廓绘制在“盒子之上”，即轮廓始终位于顶部，并且不影响盒子或其他任何盒子的定位或尺寸。因此，显示或隐藏轮廓不会导致重排。

```java
public String OutlineColor { get; set; }
```

### 返回值

normal - 元素不会相对于双向算法打开额外的嵌套层级。对于行内元素，隐式重排会跨元素边界进行。embed - 如果元素是行内级别，此值会相对于双向算法打开额外的嵌套层级。该嵌套层级的方向由 ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) 属性决定。元素内部的重排是隐式完成的。这相当于在元素开头添加 LRE（U+202A；对应 'direction: ltr'）或 RLE（U+202B；对应 'direction: rtl'），在元素结尾添加 PDF（U+202C）。bidi-override - 如果元素是行内级别或仅包含行内元素的块级元素，则会创建覆盖。这意味着在元素内部，重排严格按照 ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) 属性的顺序进行；双向算法的隐式部分被忽略。这相当于在元素开头添加 LRO（U+202D；对应 'direction: ltr'）或 RLO（U+202E；对应 'direction: rtl'），在元素结尾添加 PDF（U+202C）。

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
