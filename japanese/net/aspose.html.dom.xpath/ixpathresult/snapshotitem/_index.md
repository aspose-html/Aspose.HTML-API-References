---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML for .NET API リファレンス
description: IXPathResult 方法. を返します索引スナップショット コレクションの 番目のアイテムもしも索引 より大きいかリスト内のノード数と等しい場合このメソッドは戻り値を返しますヌル イテレータの結果とは異なりスナップショットは無効にはなりませんが変更された場合現在の ドキュメントに対応しない場合があります.
type: docs
weight: 90
url: /ja/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

を返します`索引`スナップショット コレクションの 番目のアイテム。もしも`索引` より大きいか、リスト内のノード数と等しい場合、このメソッドは戻り値を返します`ヌル` イテレータの結果とは異なり、スナップショットは無効にはなりませんが、変更された場合、現在の ドキュメントに対応しない場合があります.

```csharp
public Node SnapshotItem(int index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| index | Int32 | スナップショット コレクションにインデックスを付けます。 |

### 戻り値

のノード`索引`の 番目の位置`ノードリスト`、 また`ヌル` の場合、有効なインデックスではありません。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: 次の場合に発生します`結果タイプ` ではありません`UnorderedNodeSnapshot`タイプまたは`OrderedNodeSnapshot`タイプ。 |

### 関連項目

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* 名前空間 [Aspose.Html.Dom.XPath](../../ixpathresult/)
* 組み立て [Aspose.HTML](../../../)


