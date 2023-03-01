---
title: Interface ICSSRuleList
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.ICSSRuleList 界面. CSSRuleList 接口提供了 CSS 规则有序集合的抽象
type: docs
weight: 480
url: /zh/net/aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList 接口提供了 CSS 规则有序集合的抽象。

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Item](../../aspose.html.dom.css/icssrulelist/item/) { get; } | 用于通过方法 item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList) 检索 CSS 规则。此集合中的顺序表示 CSS 样式表中规则的顺序。如果索引大于或等于列表中的规则数，则返回 null. |
| [Length](../../aspose.html.dom.css/icssrulelist/length/) { get; } | 列表中 CSSRules 的数量。有效子规则索引的范围是 0 到 length-1（含）。 |

### 也可以看看

* interface [ICSSRule](../icssrule/)
* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


