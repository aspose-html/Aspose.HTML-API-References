---
title: "IXPathResult インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.xpath.IXPathResult インターフェイス。XPathResult インターフェイスは、特定のノードのコンテキスト内で XPath 1.0 式を評価した結果を表します。XPath 式の評価はさまざまな結果タイプを生む可能性があるため、このオブジェクトは結果のタイプと値を検出および操作できるようにします"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult` インターフェイスは、特定のノードのコンテキスト内で XPath 1.0 式を評価した結果を表します。XPath 式の評価はさまざまな結果タイプになる可能性があるため、このオブジェクトは結果のタイプと値を検出および操作できるようにします。

```java
public interface IXPathResult
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) このブール結果の値です。 |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) イテレータが無効になったことを示します。`resultType` が `UnorderedNodeIterator` タイプまたは `OrderedNodeIterator` タイプであり、結果が返された後にドキュメントが変更されている場合は true です。 |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) この数値結果の値です。 |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) この結果のタイプを表すコードで、http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) 列挙型で定義されています。 |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) この単一ノード結果の値で、`null` の可能性があります。 |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) 結果スナップショット内のノード数です。snapshotItem インデックスの有効な値は `0` から `snapshotLength-1` まで（両端含む）です。 |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) この文字列結果の値です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | ノード集合を反復し、次のノードを返します。ノードがもう無い場合は `null` を返します。 |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | スナップショットコレクションの `index` 番目の項目を返します。`index` がリスト内のノード数以上の場合、このメソッドは `null` を返します。イテレータ結果とは異なり、スナップショットは無効になりませんが、ドキュメントが変更された場合は現在のドキュメントと一致しない可能性があります。 |

### 関連項目

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
