---
title: "NodeListT クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.toolkit.markdown.syntax.NodeList1T クラス。NodeList の基本実装です。"
type: docs

url: /ja/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

NodeListの基本実装

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| パラメータ | 説明 |
| --- | --- |
| T | T 型。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| 抽象 [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) リスト内のノード数を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | 指定されたインデックスのノードを取得します。 |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | コレクション内のノードを取得します。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | ノードをテキストライターに書き込みます。 |

### 関連項目

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
