---
title: Interface IMediaList
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.IMediaList 界面. MediaList 接口提供了媒体有序集合的抽象但没有定义或限制该集合的实现方式空列表与包含介质all的列表相同
type: docs
weight: 580
url: /zh/net/aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList 接口提供了媒体有序集合的抽象，但没有定义或限制该集合的实现方式。空列表与包含介质“all”的列表相同。

```csharp
public interface IMediaList : IEnumerable<string>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Item](../../aspose.html.dom.css/imedialist/item/) { get; } | 返回列表中的第一个索引。如果索引大于或等于列表中的媒体数，则返回 null. 媒体索引。 |
| [Length](../../aspose.html.dom.css/imedialist/length/) { get; } | 列表中的媒体数。有效媒体的范围是 0 到 length-1（含）。 |
| [MediaText](../../aspose.html.dom.css/imedialist/mediatext/) { get; } | 媒体列表的可解析文本表示。这是一个以逗号分隔的媒体列表。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AppendMedium](../../aspose.html.dom.css/imedialist/appendmedium/)(string) | 将媒体 newMedium 添加到列表的末尾。如果 newMedium 已被使用，则首先将其删除。 |
| [DeleteMedium](../../aspose.html.dom.css/imedialist/deletemedium/)(string) | 从列表中删除 oldMedium 指示的媒体。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


