---
title: Interface ICSSImportRule
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.ICSSImportRule 界面. CSSImportRule 接口表示 CSS 样式表中的import 规则 import 规则用于从其他样式表导入样式规则
type: docs
weight: 410
url: /zh/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule 接口表示 CSS 样式表中的@import 规则。 @import 规则用于从其他样式表导入样式规则。

```csharp
public interface ICSSImportRule : ICSSRule
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | 要导入的样式表的位置。该属性将不包含 URI 周围的“url(...)”说明符。 |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | 可以使用此样式表的媒体类型列表。 |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | 此规则引用的样式表（如果已加载）。如果样式表尚未加载或将不会加载（例如，如果样式表用于用户代理不支持的媒体类型），则此属性的值为空。 |

### 也可以看看

* interface [ICSSRule](../icssrule/)
* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


