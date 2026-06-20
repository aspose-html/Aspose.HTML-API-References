---
title: "ICSS2Properties.SpeechRate"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性指定说话速度。请注意，允许使用绝对和相对关键字值（可与 font-size 对比）。这些值具有以下含义："
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/speechrate/
---
## ICSS2Properties.SpeechRate property

此属性指定说话速度。请注意，允许使用绝对和相对关键字值（可与 ['font-size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/fonts.html#propdef-font-size) 对比）。这些值具有以下含义：

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - 指定每分钟的单词数作为说话速度，该数量因语言略有差异，但在语音合成器中得到广泛支持。

x-slow - 相当于每分钟 80 个单词。

slow - 相当于每分钟 120 个单词。

中等 - 相当于每分钟 180 - 200 字。

快速 - 相当于每分钟 300 字。

超快 - 相当于每分钟 500 字。

更快 - 在当前语速基础上每分钟增加 40 字。

更慢 - 在当前语速基础上每分钟减少 40 字。

```java
public String SpeechRate { get; set; }
```

### 返回值

speech-rate 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
