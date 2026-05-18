---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Aspose.HTML for Java API 参考"
description: "MarkdownSyntaxFactory 方法。创建 InlineImageSyntaxNode"
type: docs

url: /zh/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

创建 [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/)。

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| altText | String | 替代文本。 |
| href | String | 图像的 URL。 |
| 标题 | String | 标题。 |

### 返回值

该 InlineImageSyntax。

### 另请参阅

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

创建 [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/)。

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
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

该 InlineImageSyntax。

### 另请参阅

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
