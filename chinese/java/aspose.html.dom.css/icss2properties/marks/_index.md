---
title: "ICSS2Properties.Marks"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。在高质量印刷中，标记通常添加在页面盒子之外。此属性指定是渲染十字标记、裁切标记还是两者都在页面盒子边缘之外渲染。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/marks/
---
## ICSS2Properties.Marks property

在高质量印刷中，标记通常添加在页面盒子之外。此属性指定是渲染十字标记、裁切标记还是两者都在[page box](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#page-box) 边缘之外。

裁切标记指示页面应裁剪的位置。十字标记（也称为定位标记或登记标记）用于对齐纸张。

标记仅在绝对页面盒子上可见（参见['size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-size) 属性）。在相对页面盒子中，页面盒子将与目标对齐，标记将位于可打印区域之外。

十字标记的大小、样式和位置取决于用户代理。

```java
public String Marks { get; set; }
```

### 返回值

marks 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
