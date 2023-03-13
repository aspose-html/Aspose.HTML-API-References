---
title: Interface ICSSCharsetRule
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.ICSSCharsetRule 界面. CSSCharsetRule 接口表示 CSS 样式表中的charset 规则 编码属性的值不影响 DOM 对象中文本数据的编码此编码始终为 UTF16加载样式表后编码属性的值是在charset 规则中找到的值如果原始文档中没有charset则不会创建 CSSCharsetRule 编码属性的值也可以用作样式表序列化所用编码的提示
type: docs
weight: 380
url: /zh/net/aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule 接口表示 CSS 样式表中的@charset 规则。 编码属性的值不影响 DOM 对象中文本数据的编码；此编码始终为 UTF-16。加载样式表后，编码属性的值是在@charset 规则中找到的值。如果原始文档中没有@charset，则不会创建 CSSCharsetRule。 编码属性的值也可以用作样式表序列化所用编码的提示。

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Encoding](../../aspose.html.dom.css/icsscharsetrule/encoding/) { get; set; } | 此@charset 规则中使用的编码信息。 |

### 也可以看看

* interface [ICSSRule](../icssrule/)
* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


