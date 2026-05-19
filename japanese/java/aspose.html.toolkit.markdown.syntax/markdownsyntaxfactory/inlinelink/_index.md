---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Aspose.HTML for Java API リファレンス"
description: "MarkdownSyntaxFactory メソッド。 InlineLinkSyntaxNode を作成します"
type: docs

url: /ja/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

作成します [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/)。

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
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

この InlineLinkSyntax。

### 関連項目

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

InlineLink を作成します。

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| テキスト | 文字列 | このリンクテキスト。 |
| destination | 文字列 | この String の宛先。 |
| タイトル | 文字列 | この String のタイトル。 |

### 戻り値

この LinkReferenceDefinitionSyntax。

### 関連項目

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
