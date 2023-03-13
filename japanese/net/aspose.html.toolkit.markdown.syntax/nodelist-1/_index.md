---
title: Class NodeListT
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Toolkit.Markdown.Syntax.NodeList1T クラス. NodeList の基本実装
type: docs
weight: 5280
url: /ja/net/aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

NodeList の基本実装。

```csharp
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| パラメータ | 説明 |
| --- | --- |
| T | T型です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [Count](../../aspose.html.toolkit.markdown.syntax/nodelist-1/count/) { get; } | リスト内のノード数を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Get](../../aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | 指定されたインデックスのノードを取得します。 |
| abstract [GetEnumerator](../../aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | コレクション内のノードを取得します。 |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | ノードをテキスト ライターに書き込みます。 |

### 関連項目

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* 名前空間 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 組み立て [Aspose.HTML](../../)


