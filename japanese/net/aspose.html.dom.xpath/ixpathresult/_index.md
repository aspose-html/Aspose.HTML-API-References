---
title: Interface IXPathResult
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.XPath.IXPathResult インターフェース. XPathResultインターフェイスは特定のノードのコンテキスト内で XPath 1.0 式を評価した結果を表します XPath 式の評価 はさまざまな結果タイプをもたらす可能性があるためこのオブジェクトを使用すると 結果のタイプと値を検出して操作できます.
type: docs
weight: 2600
url: /ja/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult`インターフェイスは、特定のノードのコンテキスト内で XPath 1.0 式を評価した結果を表します。 XPath 式の評価 はさまざまな結果タイプをもたらす可能性があるため、このオブジェクトを使用すると、 結果のタイプと値を検出して操作できます.

```csharp
public interface IXPathResult
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | このブール結果の値。 |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | イテレータが無効になったことを示します。真の場合`結果タイプ` は`UnorderedNodeIterator`タイプまたは`OrderedNodeIterator`type および この結果が返されてからドキュメントが変更されました. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | この数値結果の値. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult で定義されている、この結果のタイプを表すコード[`XPathResultType`](../xpathresulttype/)enum. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | この単一ノードの結果の値。`ヌル`. |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | 結果スナップショットのノード数。 snapshotItem インデックスの有効な値は次のとおりです。`0`に`スナップショットの長さ-1`含む. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | この文字列結果の値。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | ノード セットから次のノードを繰り返して返します。`ヌル`これ以上ノードがない場合. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | を返します`索引`スナップショット コレクションの 番目のアイテム。もしも`索引` より大きいか、リスト内のノード数と等しい場合、このメソッドは戻り値を返します`ヌル` イテレータの結果とは異なり、スナップショットは無効にはなりませんが、変更された場合、現在の ドキュメントに対応しない場合があります. |

### 関連項目

* 名前空間 [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* 組み立て [Aspose.HTML](../../)


