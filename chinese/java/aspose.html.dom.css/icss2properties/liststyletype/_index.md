---
title: "ICSS2Properties.ListStyleType"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性指定列表项标记的外观，当 list-style-image 的值为 none 或 URI 指向的图像无法显示时。值 none 表示没有标记，否则有三种标记类型：字形、编号系统和字母系统。注意：有序列表通过使列表更易于导航来提升文档可访问性。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/liststyletype/
---
## ICSS2Properties.ListStyleType property

此属性指定列表项标记的外观，如果 ['list-style-image'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-image) 的值为 'none'，或 URI 指向的图像无法显示。值 'none' 表示没有标记，否则有三种标记类型：字形、编号系统和字母系统。注意：有序列表通过使列表更易于导航来提升文档可访问性。

字形使用 disc、circle 和 square 指定。它们的具体渲染取决于用户代理。

编号系统使用以下方式指定：

decimal - 十进制数字，从 1 开始。decimal-leading-zero - 前置零的十进制数字（例如 01、02、03、...、98、99）。lower-roman - 小写罗马数字 (i, ii, iii, iv, v, 等)。upper-roman - 大写罗马数字 (I, II, III, IV, V, 等)。hebrew - 传统希伯来数字。georgian - 传统格鲁吉亚数字 (an, ban, gan, ..., he, tan, in, in-an, ...)。armenian - 传统亚美尼亚数字。cjk-ideographic - 普通表意数字。hiragana - a, i, u, e, o, ka, ki, ...。katakana - A, I, U, E, O, KA, KI, ...。hiragana-iroha - i, ro, ha, ni, ho, he, to, ...。katakana-iroha - I, RO, HA, NI, HO, HE, TO, ...

```java
public String ListStyleType { get; set; }
```

### 返回值

list-style-type 属性

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
