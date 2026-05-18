---
title: "ICSSCharsetRule 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSCharsetRule 接口。CSSCharsetRule 接口表示 CSS 样式表中的字符集规则。encoding 属性的值不影响 DOM 对象中文本数据的编码，始终为 UTF-16。样式表加载后，encoding 属性的值为字符集规则中找到的值。如果原始文档中没有字符集，则不会创建 CSSCharsetRule。encoding 属性的值也可用作序列化样式表时使用的编码的提示。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule 接口表示 CSS 样式表中的 @charset 规则。encoding 属性的值不影响 DOM 对象中文本数据的编码；该编码始终为 UTF-16。样式表加载后，encoding 属性的值即为 @charset 规则中找到的值。如果原始文档中没有 @charset，则不会创建 CSSCharsetRule。encoding 属性的值也可用作序列化样式表时使用的编码的提示。

```java
public interface ICSSCharsetRule : ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### 另请参阅

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
