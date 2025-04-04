---
title: MarkdownFeatures Enum
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.MarkdownFeatures enum. A MarkdownFeatures flag set is a set of zero or more of the following flags which are used to select elements converted to markdown
type: docs

url: /java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

A `MarkdownFeatures` flag set is a set of zero or more of the following flags, which are used to select elements converted to markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| InlineHTML | `1` | This flag enables HTML elements inlining. If this flag is set than block level elements (such as `div`) whose `markdown` attribute value equals `inline` will be inserted in to resulting markdown. |
| AutomaticParagraph | `2` | This flag enables conversion of `paragraph` elements. Content of such elements will be placed on separate lines, so markdown handlers will wrap it. |
| Header | `4` | This flag enables conversion of `header` elements. |
| Blockquote | `8` | This flag enables conversion of `blockquote` elements. |
| List | `10` | This flag enables conversion of `list` elements. |
| CodeBlock | `20` | This flag enables conversion of code blocks. Code block consists of 2 elements `pre` and `code`, content of such construction is processes "as is". |
| HorizontalRule | `40` | This flag enables conversion of `horizontal rules`. |
| Link | `80` | This flag enables conversion of `a` elements. |
| Emphasis | `100` | This flag enables conversion of `emphasis` elements. |
| InlineCode | `200` | This flag enables conversion of `code` elements. |
| Image | `400` | This flag enables conversion of `img` elements. |
| LineBreak | `800` | This flag enables conversion of `br` elements. |
| Video | `1000` | This flag enables conversion of `video` elements. |
| Table | `2000` | This flag enables conversion of `table` elements. |
| TaskList | `4000` | This flag enables conversion of task lists. Task list consists of `input` element, which must be the first child of `list` element and whose `type` attribute value should equal `checkbox`. |
| Strikethrough | `8000` | This flag enables conversion of `del` elements. |
| Strong | `10000` | This flag enables conversion of `strong` elements. |

### See Also

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
