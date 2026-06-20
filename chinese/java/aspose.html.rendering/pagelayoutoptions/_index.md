---
title: "PageLayoutOptions 枚举"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.PageLayoutOptions 枚举。指定与其他 PageSetup 选项一起决定页面大小和布局的标志。这些标志可以根据其描述进行组合。"
type: docs

url: /zh/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

指定与其他 PageSetup 选项一起决定页面尺寸和布局的标志。这些标志可根据其描述进行组合。

```java
[Flags]
public enum PageLayoutOptions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 默认值，表示 PageLayoutOptions 不会影响页面的大小和布局。 |
| FitToContentWidth | `1` | 此标志指示页面的宽度由内容大小本身决定，而不是由指定的页面宽度决定。内容的宽度会为每个页面单独计算。 |
| UseWidestPage | `2` | 当与 FitToContentWidth 组合时，表示每个页面的宽度将相同，并且等于所有页面中最宽的内容大小。 |
| FitToWidestContentWidth | `3` | 此标志指示页面的宽度由内容大小本身决定，而不是由指定的页面宽度决定。每个页面的宽度将相同，并且等于所有页面中最宽的内容大小。 |
| FitToContentHeight | `10` | 此标志指示页面的高度由内容大小本身决定，而不是由指定的页面高度决定。如果指定此标志，所有文档内容将位于单个页面上。 |
| ScaleToPageWidth | `100` | 此标志指示文档内容将按比例缩放以适应页面，其中可用页面宽度与重叠内容之间的差异最大。它与 FitToContentWidth 标志冲突，如果同时指定两个标志，则仅 ScaleToPageWidth 生效。 |
| ScaleToPageHeight | `1000` | 此标志指示文档内容将按比例缩放以适应第一页的高度。它与 FitToContentHeight 标志冲突，如果同时指定两个标志，则仅 ScaleToPageHeight 生效。所有文档内容仅会放置在单个页面上。 |

### 另请参见

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
