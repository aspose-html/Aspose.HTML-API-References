---
title: Class MarkdownSyntaxTree
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree クラス. Markdown 構文ツリーを表します
type: docs
weight: 5220
url: /ja/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Markdown 構文ツリーを表します。

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | MarkdownSyntaxTree を作成しました。 |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | MarkdownSyntaxTree を作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | 最初の子を取得します。 |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | 最後の子を取得します。 |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | 次の兄弟を取得します。 |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | 親ノードを取得します。 |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | 前の兄弟を取得します。 |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | SyntaxFactory を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | 構文ツリーのノードにアクセスするためのインターフェイスを定義します。 |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 子ノードを追加します。 |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 子ノード コレクションを取得します。 |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | ノード イテレータを作成するためのインターフェイスを定義します。 |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | ノード イテレータを作成するためのインターフェイスを定義します。 |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | ノード イテレータを作成するためのインターフェイスを定義します。 |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | ツリー ウォーカーを作成するためのインターフェイスを定義します。 |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | ツリー ウォーカーを作成するためのインターフェイスを定義します。 |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | ツリー ウォーカーを作成するためのインターフェイスを定義します。 |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 一流のトリビアを手に入れよう. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 構文ツリーを取得します。 |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 末尾のトリビアを取得します。 |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | ノードの前に挿入. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 子を削除します。 |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 子ノードを置き換えます。 |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | 構文ツリーを指定されたストリームに保存します。 |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | 構文ツリーを指定されたパスに保存します。 |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | 指定したライターに構文ツリーを保存します。 |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString メソッドをオーバーライドします。 |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter に書き込みます。 |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | ノードをテキスト ライターに書き込みます。 |

### 関連項目

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* 名前空間 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 組み立て [Aspose.HTML](../../)


