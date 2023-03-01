---
title: Interface ICSSRule
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.ICSSRule 界面. CSSRule 接口是任何类型的CSS 语句的抽象基接口这包括规则集和规则期望实现保留 CSS 样式表中指定的所有规则即使解析器无法识别该规则无法识别的规则使用ICSSUnknownRule接口.
type: docs
weight: 470
url: /zh/net/aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule 接口是任何类型的CSS 语句的抽象基接口。这包括规则集和规则。期望实现保留 CSS 样式表中指定的所有规则，即使解析器无法识别该规则。无法识别的规则使用!:ICSSUnknownRule接口.

```csharp
public interface ICSSRule
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssrule/csstext/) { get; set; } | 规则的可解析文本表示。这反映了规则的当前状态，而不是其初始值。 |
| [ParentRule](../../aspose.html.dom.css/icssrule/parentrule/) { get; } | 如果此规则包含在另一个规则中（例如@media 块中的样式规则），则这是包含规则。如果此规则未嵌套在任何其他规则中，则返回 null. |
| [ParentStyleSheet](../../aspose.html.dom.css/icssrule/parentstylesheet/) { get; } | 包含此规则的样式表。 |
| [Type](../../aspose.html.dom.css/icssrule/type/) { get; } | 规则的类型，如上定义。预期是特定于绑定的转换方法可用于从 CSSRule 接口的实例向下转换为类型隐含的特定派生接口。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


