---
title: MarkdownFeatures enumeration
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 140
url: /python-net/aspose.html.saving/markdownfeatures/
is_root: false
---

## MarkdownFeatures enumeration

A [`MarkdownFeatures`](/html/python-net/aspose.html.saving/markdownfeatures) flag set is a set of zero or more of the following flags, which are used to select elements converted to markdown.



The MarkdownFeatures type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| INLINE_HTML | This flag enables HTML elements inlining. If this flag is set than block level elements (such as `div`) whose `markdown` attribute value equals `inline` will be inserted in to resulting markdown. |
| AUTOMATIC_PARAGRAPH | This flag enables conversion of `paragraph` elements. Content of such elements will be placed on separate lines, so markdown handlers will wrap it. |
| HEADER | This flag enables conversion of `header` elements. |
| BLOCKQUOTE | This flag enables conversion of `blockquote` elements. |
| LIST | This flag enables conversion of `list` elements. |
| CODE_BLOCK | This flag enables conversion of code blocks. Code block consists of 2 elements `pre` and `code`, content of such construction is processes "as is". |
| HORIZONTAL_RULE | This flag enables conversion of `horizontal rules`. |
| LINK | This flag enables conversion of `a` elements. |
| EMPHASIS | This flag enables conversion of `emphasis` elements. |
| INLINE_CODE | This flag enables conversion of `code` elements. |
| IMAGE | This flag enables conversion of `img` elements. |
| LINE_BREAK | This flag enables conversion of `br` elements. |
| VIDEO | This flag enables conversion of `video` elements. |
| TABLE | This flag enables conversion of `table` elements. |
| TASK_LIST | This flag enables conversion of task lists. Task list consists of `input` element, which must be the first child of `list` element and whose `type` attribute value should equal `checkbox`. |
| STRIKETHROUGH | This flag enables conversion of `del` elements. |
| STRONG | This flag enables conversion of `strong` elements. |



### See Also
* module [`aspose.html.saving`](..)
* class [`MarkdownFeatures`](/html/python-net/aspose.html.saving/markdownfeatures)
