---
title: "ICSSImportRule 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSImportRule 接口。CSSImportRule 接口表示 CSS 样式表中的导入规则。该导入规则用于从其他样式表导入样式规则。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule 接口表示 CSS 样式表中的 @import 规则。@import 规则用于从其他样式表导入样式规则。

```java
public interface ICSSImportRule : ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getHref](../../com.aspose.html.dom.css/icssimportrule/href/) CSSImportRule 接口的只读 href 属性返回 @import at-rule 指定的 URL。 |
| [getMedia](../../com.aspose.html.dom.css/icssimportrule/media/) CSSImportRule 接口的只读 media 属性返回一个 MediaList 对象，包含关联样式表的 media 属性值。 |
| [getStyleSheet](../../com.aspose.html.dom.css/icssimportrule/stylesheet/) 此规则引用的样式表（如果已加载）。如果样式表尚未加载或不会被加载（例如样式表针对用户代理不支持的媒体类型），则此属性的值为 null。 |

### 另请参见

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
