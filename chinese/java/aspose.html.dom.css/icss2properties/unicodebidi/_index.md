---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性的取值具有以下含义"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

此属性的取值具有以下含义：

normal - 元素在双向算法中不会打开额外的嵌套层级。对于行内元素，隐式重排会跨越元素边界进行。embed - 如果元素是行内级别的，则此值会在双向算法中打开一个额外的嵌套层级。该嵌套层级的方向由 ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) 属性决定。元素内部，重排会隐式完成。这相当于在元素开头添加 LRE（U+202A；对应 'direction: ltr'）或 RLE（U+202B；对应 'direction: rtl'），并在元素结尾添加 PDF（U+202C）。bidi-override - 如果元素是行内级别的，或是仅包含行内元素的块级元素，则会创建覆盖。这意味着在元素内部，重排严格按照 ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) 属性的顺序进行；双向算法的隐式部分被忽略。这相当于在元素开头添加 LRO（U+202D；对应 'direction: ltr'）或 RLO（U+202E；对应 'direction: rtl'），并在元素结尾添加 PDF（U+202C）。

```java
public String UnicodeBidi { get; set; }
```

### 返回值

unicode-bidi 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
