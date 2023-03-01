---
title: Interface ICSSKeyframesRule
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.ICSSKeyframesRule 界面. CSSKeyframesRule 接口表示单个动画的一组完整关键帧
type: docs
weight: 430
url: /zh/net/aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframesRule 接口表示单个动画的一组完整关键帧

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icsskeyframesrule/cssrules/) { get; } | 此属性可以访问列表中的关键帧 |
| [Name](../../aspose.html.dom.css/icsskeyframesrule/name/) { get; } | 此属性是关键帧的名称，由“动画名称”属性使用。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AppendRule](../../aspose.html.dom.css/icsskeyframesrule/appendrule/)(string) | appendRule 方法将传递的 CSSKeyframeRule 附加到列表中传递的 key |
| [DeleteRule](../../aspose.html.dom.css/icsskeyframesrule/deleterule/)(string) | deleteRule 方法使用传递的键删除 CSSKeyframeRule。如果不存在具有此键的规则，则该方法不执行任何操作 |
| [FindRule](../../aspose.html.dom.css/icsskeyframesrule/findrule/)(string) | findRule 方法返回具有与传递的键匹配的键的规则。如果不存在这样的规则，则返回空值 |

### 也可以看看

* interface [ICSSRule](../icssrule/)
* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


