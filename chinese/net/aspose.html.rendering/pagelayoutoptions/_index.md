---
title: Enum PageLayoutOptions
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Rendering.PageLayoutOptions 枚举. 指定与其他 PageSetup 选项一起确定页面大小和布局的标志 这些标志可以根据它们的描述组合在一起
type: docs
weight: 4380
url: /zh/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

指定与其他 PageSetup 选项一起确定页面大小和布局的标志。 这些标志可以根据它们的描述组合在一起。

```csharp
[Flags]
public enum PageLayoutOptions
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| None | `0` | 默认值表示 PageLayoutOptions 不会影响页面的大小和布局。 |
| FitToContentWidth | `1` | 此标志表示页面的宽度由内容大小本身决定，而不是根据指定的页面宽度。 内容的宽度是为每个页面单独计算的。 |
| UseWidestPage | `2` | 结合时FitToContentWidth指示每个页面的宽度将相同，并且将等于所有页面中最宽的内容大小。 |
| FitToWidestContentWidth | `3` | 这个标志表示页面的宽度是由内容大小本身决定的，而不是由指定的页面宽度决定的。 每个页面的宽度将是相同的，并且将等于所有页面中最宽的内容大小。 |
| FitToContentHeight | `10` | 该标志表示页面的高度由内容大小本身决定，而不是根据指定的页面高度。 如果指定该标志，所有文档内容将位于单个页面上。 |
| ScaleToPageWidth | `100` | 此标志表示文档的内容将被缩放以适应可用页面宽度与重叠内容之间差异最大的页面。 它与FitToContentWidth标志，如果仅指定了两个标志ScaleToPageWidth会生效. |
| ScaleToPageHeight | `1000` | 这个标志表示文档的内容将被缩放以适合第一页的高度。 它与FitToContentHeight标志，如果仅指定了两个标志ScaleToPageHeight将生效。 所有文档内容将仅放在单个页面上。 |

### 也可以看看

* 命名空间 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 部件 [Aspose.HTML](../../)


