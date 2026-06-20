---
title: "ICSS2Properties.WhiteSpace"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性声明元素内部空白字符的处理方式。取值含义如下："
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

此属性声明元素内部[whitespace](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace)的处理方式。取值含义如下：

normal - 此值指示用户代理折叠空白字符序列，并在必要时换行以填充行框。生成内容中出现 "\A" 时可能会产生额外的换行（例如 HTML 中的 BR 元素）。pre - 此值阻止用户代理折叠空白字符序列。换行仅在源文件中的换行符或生成内容中出现 "\A" 时进行。nowrap - 此值的空白折叠方式与 'normal' 相同，但除生成内容中出现的 "\A" 所导致的换行外，抑制文本内部的换行（例如 HTML 中的 BR 元素）。

```java
public String WhiteSpace { get; set; }
```

### 返回值

white-space 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
