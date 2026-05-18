---
title: "ICSS2Properties.PauseBefore"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。这些属性指定在朗读元素内容之前或之后应观察的暂停。值具有以下含义"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/pausebefore/
---
## ICSS2Properties.PauseBefore property

这些属性指定在朗读元素的内容之前（或之后）应观察的暂停。值具有以下含义：

'[time](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-time)' - 以绝对时间单位（秒和毫秒）表示暂停。'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - 参考 ['speech-rate'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-speech-rate) 属性值的倒数。例如，如果 speech-rate 为每分钟 120 个单词（即每个单词半秒，或 500ms），则 ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) 为 100% 表示暂停 500 毫秒，而 ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) 为 20% 表示 100 毫秒。

```java
public String PauseBefore { get; set; }
```

### 返回值

pause-before 属性

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
