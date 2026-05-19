---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IXPathResult メソッド。スナップショットコレクションの index 番目の項目を返します。index がリスト内のノード数以上の場合、このメソッドは null を返します。イテレータ結果とは異なり、スナップショットは無効になりませんが、ドキュメントが変更された場合は現在のドキュメントと一致しない可能性があります。"
type: docs

url: /ja/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

スナップショットコレクションの `index` 番目の項目を返します。`index` がリスト内のノード数以上の場合、このメソッドは `null` を返します。イテレータ結果とは異なり、スナップショットは無効になりませんが、ドキュメントが変更された場合は現在のドキュメントと一致しない可能性があります。

```java
public Node SnapshotItem(int index)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| index | Int32 | スナップショットコレクションへのインデックス。 |

### 戻り値

`NodeList` の `index` 番目の位置にあるノード、または有効なインデックスでない場合は `null`。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: `resultType` が `UnorderedNodeSnapshot` 型または `OrderedNodeSnapshot` 型でない場合に発生します。 |

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
