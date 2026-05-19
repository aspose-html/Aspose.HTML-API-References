---
title: "HugoYamlBasedFrontMatterSyntaxNode クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.toolkit.markdown.syntax.extensions.HugoYamlBasedFrontMatterSyntaxNode クラス。HugoYamlBasedFrontMatterSyntaxNode を定義します。"
type: docs

url: /ja/java/com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/
---
## HugoYamlBasedFrontMatterSyntaxNode class

HugoYamlBasedFrontMatterSyntaxNode を定義します。

```java
public class HugoYamlBasedFrontMatterSyntaxNode : HugoFrontMatterSyntaxNode, 
    IEnumerable<KeyValuePair<ChildFrontMatterSyntaxNode, ChildFrontMatterSyntaxNode>>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) 最初の子ノードを取得します。 |
| [getFrontMatterRootNode](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/frontmatterrootnode/) RootNode を取得します。 |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) 最後の子ノードを取得します。 |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) 次の兄弟ノードを取得します。 |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) 親ノードを取得します。 |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) 前の兄弟ノードを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | ビジター受け入れ用インターフェイスを定義します。 |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 子ノードを追加します。 |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 子ノードのコレクションを取得します。 |
| [find](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/)(params String[]) | BaseSyntaxNode を検索するインターフェイスを定義します。 |
| [Find&lt;T&gt;](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/find/#find_1)(params String[]) | 文字列パスで T を検索するインターフェイスを定義します。 |
| [getEnumerator](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/getenumerator/)() | 列挙子を取得します。 |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 先頭のトリビアを取得します。 |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 構文ツリーを取得します。 |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 末尾のトリビアを取得します。 |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | ノードの前に挿入します。 |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 子ノードを削除します。 |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 子ノードを置き換えます。 |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | ToString メソッドをオーバーライドします。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter に書き込みます。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | ノードをテキストライターに書き込みます。 |

### 関連項目

* class [HugoFrontMatterSyntaxNode](../hugofrontmattersyntaxnode/)
* class [ChildFrontMatterSyntaxNode](../childfrontmattersyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax.extensions](../../com.aspose.html.toolkit.markdown.syntax.extensions/)
* package [Aspose.HTML](../../)
