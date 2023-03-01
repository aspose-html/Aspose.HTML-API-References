---
title: Class HugoYamlBasedFrontMatterSyntaxNode
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Toolkit.Markdown.Syntax.Extensions.HugoYamlBasedFrontMatterSyntaxNode クラス. HugoYamlBasedFrontMatterSyntaxNode を定義します
type: docs
weight: 4940
url: /ja/net/aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/
---
## HugoYamlBasedFrontMatterSyntaxNode class

HugoYamlBasedFrontMatterSyntaxNode を定義します

```csharp
public class HugoYamlBasedFrontMatterSyntaxNode : HugoFrontMatterSyntaxNode, 
    IEnumerable<KeyValuePair<string, ChildFrontMatterSyntaxNode>>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | 最初の子を取得します。 |
| override [FrontMatterRootNode](../../aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/frontmatterrootnode/) { get; } | RootNode を取得および設定します。 |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | 最後の子を取得します。 |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | 次の兄弟を取得します。 |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | 親ノードを取得します。 |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | 前の兄弟を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | 訪問者を受け入れるためのインターフェイスを定義します. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 子ノードを追加します。 |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 子ノード コレクションを取得します。 |
| [Find](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/)(params string[]) | find BaseSyntaxNode のインターフェイスを定義します |
| override [Find&lt;T&gt;](../../aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/find/#find_1)(params string[]) | 文字列で T を検索するためのインターフェイスを定義します Path |
| [GetEnumerator](../../aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/getenumerator/)() | 列挙子を取得します。 |
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

* class [HugoFrontMatterSyntaxNode](../hugofrontmattersyntaxnode/)
* class [ChildFrontMatterSyntaxNode](../childfrontmattersyntaxnode/)
* 名前空間 [Aspose.Html.Toolkit.Markdown.Syntax.Extensions](../../aspose.html.toolkit.markdown.syntax.extensions/)
* 組み立て [Aspose.HTML](../../)


