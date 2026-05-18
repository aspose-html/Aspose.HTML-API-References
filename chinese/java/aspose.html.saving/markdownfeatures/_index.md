---
title: "MarkdownFeatures 枚举"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.MarkdownFeatures 枚举。MarkdownFeatures 标志集是以下零个或多个标志的集合，用于选择要转换为 markdown 的元素。"
type: docs

url: /zh/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

`MarkdownFeatures` 标志集是以下零个或多个标志的集合，用于选择要转换为 markdown 的元素。

```java
[Flags]
public enum MarkdownFeatures
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| InlineHTML | `1` | 此标志启用 HTML 元素内联。如果设置此标志，则块级元素（如 `div`）其 `markdown` 属性值等于 `inline` 将被插入到生成的 markdown 中。 |
| AutomaticParagraph | `2` | 此标志启用对 `paragraph` 元素的转换。此类元素的内容将放在单独的行上，markdown 处理器会对其进行换行。 |
| Header | `4` | 此标志启用对 `header` 元素的转换。 |
| Blockquote | `8` | 此标志启用对 `blockquote` 元素的转换。 |
| List | `10` | 此标志启用对 `list` 元素的转换。 |
| CodeBlock | `20` | 此标志启用对代码块的转换。代码块由两个元素 `pre` 和 `code` 组成，此类结构的内容将按原样处理。 |
| HorizontalRule | `40` | 此标志启用对 `horizontal rules` 的转换。 |
| Link | `80` | 此标志启用对 `a` 元素的转换。 |
| Emphasis | `100` | 此标志启用对 `emphasis` 元素的转换。 |
| InlineCode | `200` | 此标志启用对 `code` 元素的转换。 |
| Image | `400` | 此标志启用对 `img` 元素的转换。 |
| LineBreak | `800` | 此标志启用对 `br` 元素的转换。 |
| Video | `1000` | 此标志启用对 `video` 元素的转换。 |
| Table | `2000` | 此标志启用对 `table` 元素的转换。 |
| TaskList | `4000` | 此标志启用对任务列表的转换。任务列表由 `input` 元素组成，该元素必须是 `list` 元素的第一个子元素，并且其 `type` 属性值应等于 `checkbox`。 |
| Strikethrough | `8000` | 此标志启用对 `del` 元素的转换。 |
| Strong | `10000` | 此标志启用对 `strong` 元素的转换。 |

### 另请参阅

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
