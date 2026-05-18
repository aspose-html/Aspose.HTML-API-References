---
title: "ICSS2Properties.SpeechRate"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性指定说话速率。注意，允许使用绝对和相对关键字值，可与 font-size 进行比较。这些值具有以下含义。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/speechrate/
---
## ICSS2Properties.SpeechRate property

此属性指定说话速率。注意，允许使用绝对和相对关键字值（可与 ['font-size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/fonts.html#propdef-font-size) 比较）。这些值具有以下含义：

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - 指定每分钟的单词数作为说话速率，该数量因语言略有差异，但在语音合成器中被广泛支持。

x-slow - 相当于每分钟 80 个单词。

slow - 相当于每分钟 120 个单词。

中等 - 相当于每分钟 180 - 200 词。

快速 - 相当于每分钟 300 词。

超快 - 相当于每分钟 500 词。

更快 - 在当前语速上增加每分钟 40 词。

更慢 - 在当前语速上减少每分钟 40 词。

```java
public String SpeechRate { get; set; }
```

### 返回值

speech-rate 属性

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
