---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Aspose.HTML for Java API 参考"
description: "MarkdownSyntaxFactory 方法。创建 InlineLinkSyntaxNode"
type: docs

url: /zh/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

创建 [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/)。

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | 该 contentOpening。 |
| contentClosing | MarkdownSyntaxToken | 该 contentClosing。 |
| declarationOpening | MarkdownSyntaxToken | 该 declarationOpening。 |
| destination | LinkDestinationSyntaxNode | 该 destination。 |
| 标题 | LinkTitleSyntaxNode | 标题。 |
| declarationClosing | MarkdownSyntaxToken | 该 declarationClosing。 |

### 返回值

该 InlineLinkSyntax。

### 另请参阅

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

创建 InlineLink。

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 链接文本。 |
| destination | String | 该 String 目标。 |
| 标题 | String | 该 String 标题。 |

### 返回值

该 LinkReferenceDefinitionSyntax。

### 另请参阅

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
