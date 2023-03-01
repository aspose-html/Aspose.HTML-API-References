---
title: SVGListBase1.Item
second_title: Aspose.HTML for .NET API リファレンス
description: SVGListBase 財産. リストのインデックス番目の項目を返します
type: docs
weight: 10
url: /ja/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

リストのインデックス番目の項目を返します。

```csharp
public T this[ulong index] { get; set; }
```

| パラメータ | 説明 |
| --- | --- |
| index | リスト内のインデックス。 |

### 戻り値

リスト内の index 番目の位置に格納されているオブジェクト。

### プロパティ値

リストに格納されているアイテムのタイプ.

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). リストを変更できない場合に発生します。 |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). インデックス番号が numberOfItems 以上の場合に発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* 名前空間 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 組み立て [Aspose.HTML](../../../)


