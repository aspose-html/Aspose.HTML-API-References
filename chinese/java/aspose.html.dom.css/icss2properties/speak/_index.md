---
title: "ICSS2Properties.Speak"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性指定文本是否以听觉方式呈现，以及如果是，以何种方式呈现，某种程度上类似于 display 属性。可能的取值有"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

此属性指定文本是否以听觉方式呈现，以及如果是，以何种方式（在某种程度上类似于 ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) 属性）。可能的取值有：

none - 抑制听觉渲染，使元素无需时间进行渲染。然而请注意，后代元素可能会覆盖此值并被朗读。（若要确保抑制元素及其后代的渲染，请使用 ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) 属性）。normal - 使用基于语言的发音规则来渲染元素及其子元素。spell-out - 将文本逐字拼写（对首字母缩写和缩写词有用）。

```java
public String Speak { get; set; }
```

### 返回值

speak 属性

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
