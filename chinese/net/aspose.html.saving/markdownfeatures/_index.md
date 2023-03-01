---
title: Enum MarkdownFeatures
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Saving.MarkdownFeatures 枚举. 一个MarkdownFeatures flag set 是一组零个或多个以下标志用于选择转换为 markdown. 的元素
type: docs
weight: 4620
url: /zh/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

一个`MarkdownFeatures` flag set 是一组零个或多个以下标志，用于选择转换为 markdown. 的元素

```csharp
[Flags]
public enum MarkdownFeatures
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| InlineHTML | `1` | 此标志启用 HTML 元素内联。如果设置了这个标志而不是块级元素（例如`分区`） 谁的`降价`属性值等于`排队`将被插入到结果降价中。 |
| AutomaticParagraph | `2` | 此标志启用转换`段落`元素。此类元素的内容将放在单独的行中，因此降价处理程序会将其包装。 |
| Header | `4` | 此标志启用转换`标头`元素. |
| Blockquote | `8` | 此标志启用转换`块引用`元素. |
| List | `10` | 此标志启用转换`列表`元素. |
| CodeBlock | `20` | 此标志启用代码块的转换。代码块由2个元素组成`前`和`代码`，此类建设的内容是“按原样”进行的。 |
| HorizontalRule | `40` | 此标志启用转换`横向规则`. |
| Link | `80` | 此标志启用转换`A`元素. |
| Emphasis | `100` | 此标志启用转换`强调`元素. |
| InlineCode | `200` | 此标志启用转换`代码`元素. |
| Image | `400` | 此标志启用转换`图片`元素. |
| LineBreak | `800` | 此标志启用转换`br`元素. |
| Video | `1000` | 此标志启用转换`视频`元素. |
| Table | `2000` | 此标志启用转换`桌子`元素. |
| TaskList | `4000` | 此标志启用任务列表的转换。任务清单包括`输入`元素，它必须是第一个孩子`列表`元素及其`类型`属性值应该相等`复选框`. |
| Strikethrough | `8000` | 此标志启用转换`德尔`元素. |
| Strong | `10000` | 此标志启用转换`强的`元素. |

### 也可以看看

* 命名空间 [Aspose.Html.Saving](../../aspose.html.saving/)
* 部件 [Aspose.HTML](../../)


