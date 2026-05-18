---
title: "ICSS2Properties.Overflow"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性指定当块级元素的内容溢出其作为内容包含块的元素盒子时，是否被裁剪。取值含义如下"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

此属性指定当块级元素的内容溢出该元素的盒子（该盒子充当内容的包含块）时，是否被裁剪。取值含义如下：

visible - 该取值表示内容未被裁剪，即可能在块盒子之外渲染。hidden - 该取值表示内容被裁剪，并且不应提供滚动机制来查看裁剪区域之外的内容；用户无法访问被裁剪的内容。裁剪区域的大小和形状由['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip)属性指定。scroll - 该取值表示内容被裁剪，并且如果用户代理使用在屏幕上可见的滚动机制（如滚动条或平移器），则应为盒子显示该机制，无论其内容是否被裁剪。这可避免在动态环境中滚动条出现和消失的问题。当该取值在目标介质为 'print' 或 'projection' 时指定，溢出内容应被打印。auto - “auto”取值的行为取决于用户代理，但应为溢出盒子提供滚动机制。

```java
public String Overflow { get; set; }
```

### 返回值

overflow 属性

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
