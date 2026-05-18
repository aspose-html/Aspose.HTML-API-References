---
title: "ICSS2Properties.WhiteSpace"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性声明元素内部的空白字符如何处理。取值含义如下："
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

此属性声明元素内部的[空白字符](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace)如何处理。取值含义如下：

normal - 此值指示用户代理折叠空白字符序列，并在必要时换行以填充行框。通过生成内容中出现的 "\\A"（例如 HTML 中的 BR 元素）可以创建额外的换行。pre - 此值阻止用户代理折叠空白字符序列。换行仅在源代码中的换行符或生成内容中出现的 "\\A" 处进行。nowrap - 此值的空白折叠行为与 'normal' 相同，但除生成内容中出现的 "\\A" 所创建的换行外，抑制文本内部的换行（例如 HTML 中的 BR 元素）。

```java
public String WhiteSpace { get; set; }
```

### 返回值

white-space 属性

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
