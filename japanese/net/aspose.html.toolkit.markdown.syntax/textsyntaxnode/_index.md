---
title: Class TextSyntaxNode
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Toolkit.Markdown.Syntax.TextSyntaxNode クラス. テキスト構文ノードを実装しました
type: docs
weight: 5670
url: /ja/net/aspose.html.toolkit.markdown.syntax/textsyntaxnode/
---
## TextSyntaxNode class

テキスト構文ノードを実装しました。

```csharp
public class TextSyntaxNode : InlineSyntaxNode
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | 最初の子を取得します。 |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | 最後の子を取得します。 |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | 次の兄弟を取得します。 |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | 親ノードを取得します。 |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | 前の兄弟を取得します。 |
| virtual [Source](../../aspose.html.toolkit.markdown.syntax/textsyntaxnode/source/) { get; } | ソース テキストを返します。 |
| virtual [Span](../../aspose.html.toolkit.markdown.syntax/textsyntaxnode/span/) { get; } | get span のインターフェイスを定義します。 |
| [Value](../../aspose.html.toolkit.markdown.syntax/textsyntaxnode/value/) { get; } | 文字列値を取得するためのプロパティを定義します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/textsyntaxnode/accept/)(MarkdownSyntaxVisitor) | 訪問者を受け入れるためのインターフェイスを定義します. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 子ノードを追加します。 |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 子ノード コレクションを取得します。 |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 一流のトリビアを手に入れよう. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 構文ツリーを取得します。 |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 末尾のトリビアを取得します。 |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | ノードの前に挿入. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 子を削除します。 |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 子ノードを置き換えます。 |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString メソッドをオーバーライドします。 |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter に書き込みます。 |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | ノードをテキスト ライターに書き込みます。 |

### 関連項目

* class [InlineSyntaxNode](../inlinesyntaxnode/)
* 名前空間 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 組み立て [Aspose.HTML](../../)


