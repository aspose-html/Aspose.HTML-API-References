---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML for .NET API 参考
description: MarkdownSyntaxFactory 方法. 使用 InlineLinkSyntax.CreateInstance. 创建对象
type: docs
weight: 220
url: /zh/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

使用 InlineLinkSyntax.CreateInstance. 创建对象

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | 内容开篇。 |
| contentClosing | MarkdownSyntaxToken | 内容收尾。 |
| declarationOpening | MarkdownSyntaxToken | 宣言开幕。 |
| destination | LinkDestinationSyntaxNode | 目的地。 |
| title | LinkTitleSyntaxNode | 标题。 |
| declarationClosing | MarkdownSyntaxToken | 声明结束。 |

### 返回值

内联链接语法。

### 也可以看看

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* 命名空间 [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* 部件 [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

创建 InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 链接文本。 |
| destination | String | 字符串目的地。 |
| title | String | 字符串标题。 |

### 返回值

LinkReferenceDefinitionSyntax。

### 也可以看看

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* 命名空间 [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* 部件 [Aspose.HTML](../../../)


