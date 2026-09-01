---
title: "ICSS2Properties.Clear"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性指示元素盒子的哪些侧面不能与之前的浮动盒子相邻。若元素本身有浮动子元素，clear 属性对其无效。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

此属性指示元素的盒子（们）的哪些侧面不能与之前的浮动盒子相邻。（若元素本身有浮动子元素，'clear' 属性对其无效。）

此属性只能用于块级元素（包括浮动元素）。对于 compact 和 run-in 盒子，该属性适用于其所属的最终块级盒子。

当应用于非浮动块级盒子时，取值含义如下：

left - 生成盒子的上边距增大，使其上边框位于先前文档中左浮动盒子的底部外缘以下。right - 生成盒子的上边距增大，使其上边框位于先前文档中右浮动盒子的底部外缘以下。both - 生成盒子被移动到先前文档中所有浮动盒子之下。none - 对盒子相对于浮动的定位没有约束。

```java
public String Clear { get; set; }
```

### 返回值

clear 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
