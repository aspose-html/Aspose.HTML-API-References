---
title: "MarkdownSyntaxTree クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxTree クラス。Markdown Syntax Tree を表します"
type: docs

url: /ja/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Markdown Syntax Tree を表します。

```java
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | MarkdownSyntaxTree を作成しました。 |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | MarkdownSyntaxTree を作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) 最初の子ノードを取得します。 |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) 最後の子ノードを取得します。 |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) 次の兄弟ノードを取得します。 |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) 親ノードを取得します。 |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) 前の兄弟ノードを取得します。 |
| [getSyntaxFactory](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) SyntaxFactory を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | 構文ツリーのノードを訪問するためのインターフェイスを定義します。 |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 子ノードを追加します。 |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 子ノードのコレクションを取得します。 |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | ノードイテレータを作成するためのインターフェイスを定義します。 |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | ノードイテレータを作成するためのインターフェイスを定義します。 |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | ノードイテレータを作成するためのインターフェイスを定義します。 |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | ツリーワーカーを作成するためのインターフェイスを定義します。 |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | ツリーワーカーを作成するためのインターフェイスを定義します。 |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | ツリーワーカーを作成するためのインターフェイスを定義します。 |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 先頭のトリビアを取得します。 |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 構文ツリーを取得します。 |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 末尾のトリビアを取得します。 |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | ノードの前に挿入します。 |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 子ノードを削除します。 |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 子ノードを置き換えます。 |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | 構文ツリーを指定されたストリームに保存します。 |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(String) | 構文ツリーを指定されたパスに保存します。 |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | 構文ツリーを指定されたライターに保存します。 |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | ToString メソッドをオーバーライドします。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter に書き込みます。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | ノードをテキストライターに書き込みます。 |

### 関連項目

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
