---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML for .NET API リファレンス
description: MarkdownSyntaxFactory 方法. InlineLinkSyntax.CreateInstance. を使用してオブジェクトを作成します
type: docs
weight: 220
url: /ja/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

InlineLinkSyntax.CreateInstance. を使用してオブジェクトを作成します

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | 内容オープニング。 |
| contentClosing | MarkdownSyntaxToken | 内容クロージング。 |
| declarationOpening | MarkdownSyntaxToken | 宣言オープニング。 |
| destination | LinkDestinationSyntaxNode | 目的地。 |
| title | LinkTitleSyntaxNode | タイトル。 |
| declarationClosing | MarkdownSyntaxToken | 宣言クロージング。 |

### 戻り値

InlineLinkSyntax。

### 関連項目

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* 名前空間 [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* 組み立て [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

InlineLink を作成します。

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| text | String | リンクテキスト。 |
| destination | String | 文字列の宛先。 |
| title | String | 文字列のタイトル。 |

### 戻り値

LinkReferenceDefinitionSyntax。

### 関連項目

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* 名前空間 [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* 組み立て [Aspose.HTML](../../../)


