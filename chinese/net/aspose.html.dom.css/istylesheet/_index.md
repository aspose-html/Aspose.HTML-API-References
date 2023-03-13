---
title: Interface IStyleSheet
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.IStyleSheet 界面. StyleSheet 接口是任何类型样式表的抽象基础接口它表示与结构化文档关联的单个样式表
type: docs
weight: 590
url: /zh/net/aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet 接口是任何类型样式表的抽象基础接口。它表示与结构化文档关联的单个样式表。

```csharp
public interface IStyleSheet
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Disabled](../../aspose.html.dom.css/istylesheet/disabled/) { get; set; } | false 如果样式表应用于文档。如果不是，则为真。修改此属性可能会导致文档样式的新解析。仅当存在适当的媒体定义且 disabled 属性为 false 时，样式表才适用。因此，如果媒体不适用于当前用户代理，则禁用属性将被忽略。 |
| [Href](../../aspose.html.dom.css/istylesheet/href/) { get; } | 如果样式表是一个链接样式表，它的属性值就是它的位置。对于内联样式表，该属性的值为空。 |
| [Media](../../aspose.html.dom.css/istylesheet/media/) { get; } | 样式信息的预期目标媒体。 |
| [OwnerNode](../../aspose.html.dom.css/istylesheet/ownernode/) { get; } | 将此样式表与文档相关联的节点。对于 HTML，这可能是相应的 LINK 或 STYLE 元素。对于XML，它可能是链接处理指令。对于被其他样式表包含的样式表，该属性的值为空。 |
| [ParentStyleSheet](../../aspose.html.dom.css/istylesheet/parentstylesheet/) { get; } | 对于支持样式表包含概念的样式表语言，此属性表示包含样式表（如果存在）。如果样式表是顶级样式表，或者样式表语言不支持包含，则该属性值为null. |
| [Title](../../aspose.html.dom.css/istylesheet/title/) { get; } | 咨询标题。 |
| [Type](../../aspose.html.dom.css/istylesheet/type/) { get; } | 这指定了此样式表的样式表语言。样式表语言被指定为内容类型（例如“text/css”）。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


