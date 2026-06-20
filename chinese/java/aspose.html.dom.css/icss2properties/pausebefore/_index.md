---
title: "ICSS2Properties.PauseBefore"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。这些属性指定在朗读元素内容之前或之后应观察的暂停。取值含义如下"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/pausebefore/
---
## ICSS2Properties.PauseBefore property

这些属性指定在朗读元素内容之前（或之后）应观察的暂停。取值含义如下：

'[time](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-time)' - 以绝对时间单位（秒和毫秒）表示暂停。'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - 参考 ['speech-rate'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-speech-rate) 属性值的倒数。例如，如果 speech-rate 为每分钟 120 个单词（即每个单词半秒，或 500 毫秒），则 100% 的 ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) 表示 500 毫秒的暂停，20% 的 ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) 表示 100 毫秒。

```java
public String PauseBefore { get; set; }
```

### 返回值

pause-before 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
