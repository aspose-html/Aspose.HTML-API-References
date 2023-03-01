---
title: Class PageSetup
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Rendering.PageSetup 班级. 表示页面设置对象用于配置输出页面设置
type: docs
weight: 4390
url: /zh/net/aspose.html.rendering/pagesetup/
---
## PageSetup class

表示页面设置对象用于配置输出页面设置。

```csharp
public class PageSetup
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AdjustToWidestPage](../../aspose.html.rendering/pagesetup/adjusttowidestpage/) { get; set; } | 获取或设置标志，确定何时将页面大小调整为文档中最宽的页面。 此选项非常耗时，因此文档处理时间可以增加两倍。仅当文档中的最宽页面宽度大于中确定的页面大小时，才会进行调整`PageSetup` Adjusted 页面大小将用于文档中的所有页面。 |
| [AnyPage](../../aspose.html.rendering/pagesetup/anypage/) { get; set; } | 获取或设置页面序列中的所有页面配置。 |
| [AtPagePriority](../../aspose.html.rendering/pagesetup/atpagepriority/) { get; set; } | 获取或设置[`AtPagePriority`](../atpagepriority/)这将决定应用页面大小声明的顺序。默认情况下选项将覆盖 css`@页`规则. |
| [FirstPage](../../aspose.html.rendering/pagesetup/firstpage/) { get; set; } | 获取或设置第一页配置。 |
| [LeftPage](../../aspose.html.rendering/pagesetup/leftpage/) { get; } | 获取奇数页配置。 |
| [PageLayoutOptions](../../aspose.html.rendering/pagesetup/pagelayoutoptions/) { get; set; } | 获取或设置[`PageLayoutOptions`](../pagelayoutoptions/) .默认值为None，任何其他值将覆盖[`AdjustToWidestPage`](./adjusttowidestpage/)行为。仅适用于 HTML 文档。 |
| [RightPage](../../aspose.html.rendering/pagesetup/rightpage/) { get; } | 获取偶数页配置。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetLeftRightPage](../../aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | 设置左/右页面配置。 |

### 也可以看看

* 命名空间 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 部件 [Aspose.HTML](../../)


