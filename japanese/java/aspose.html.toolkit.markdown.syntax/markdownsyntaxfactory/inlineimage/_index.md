---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Aspose.HTML for Java API リファレンス"
description: "MarkdownSyntaxFactory メソッド。InlineImageSyntaxNode を作成します。"
type: docs

url: /ja/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

作成します [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/)。

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| altText | 文字列 | 代替テキストです。 |
| href | 文字列 | 画像の URLです。 |
| タイトル | 文字列 | タイトルです。 |

### 戻り値

InlineImageSyntaxです。

### 関連項目

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

作成します [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/)。

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | contentOpeningです。 |
| contentClosing | MarkdownSyntaxToken | contentClosingです。 |
| declarationOpening | MarkdownSyntaxToken | declarationOpeningです。 |
| destination | LinkDestinationSyntaxNode | destinationです。 |
| タイトル | LinkTitleSyntaxNode | タイトルです。 |
| declarationClosing | MarkdownSyntaxToken | declarationClosingです。 |

### 戻り値

InlineImageSyntaxです。

### 関連項目

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
