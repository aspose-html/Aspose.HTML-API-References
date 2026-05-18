---
title: "ICSS2Properties.VerticalAlign"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性影响由内联级元素生成的盒子在行盒子内部的垂直定位。以下值仅在相对于父内联级元素或相对于父块级元素（如果该元素生成匿名内联盒子）时才有意义；如果不存在此类父元素，则它们没有效果。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

此属性影响由内联级元素生成的盒子在行盒子内部的垂直定位。以下值仅在相对于父内联级元素或相对于父块级元素（如果该元素生成[anonymous inline boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous)）时才有意义；如果不存在此类父元素，则它们没有效果。

注意：此属性的取值在表格上下文中含义略有不同。有关详细信息，请参阅[table height algorithms](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout)章节。baseline - 将盒子的基线与父盒子的基线对齐。如果盒子没有基线，则将盒子的底部与父盒子的基线对齐。middle - 将盒子的垂直中点与父盒子的基线加上父盒子 x 高度的一半对齐。sub - 将盒子的基线降低到父盒子下标的适当位置。（此取值不影响元素文本的字体大小。）super - 将盒子的基线提升到父盒子上标的适当位置。（此取值不影响元素文本的字体大小。）text-top - 将盒子的顶部与父元素字体的顶部对齐。text-bottom - 将盒子的底部与父元素字体的底部对齐。'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - 通过此距离（相对于 ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height) 值的百分比）将盒子上移（正值）或下移（负值）。值 '0%' 等同于 'baseline'。'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - 通过此距离将盒子上移（正值）或下移（负值）。值 '0cm' 等同于 'baseline'。top - 将盒子的顶部与行盒子的顶部对齐。bottom - 将盒子的底部与行盒子的底部对齐。

```java
public String VerticalAlign { get; set; }
```

### 返回值

vertical-align 属性

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
