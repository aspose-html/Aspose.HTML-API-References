---
title: SVGListBase1.RemoveItem
second_title: Aspose.HTML for .NET API リファレンス
description: SVGListBase 方法. リストから既存の項目を削除します
type: docs
weight: 100
url: /ja/net/aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

リストから既存の項目を削除します。

```csharp
public T RemoveItem(ulong index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| index | UInt64 | 削除するアイテムのインデックス。最初の項目は番号 0 です。 |

### 戻り値

削除されたアイテム。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). リストを変更できない場合に発生します。 |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). インデックス番号が numberOfItems 以上の場合に発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* 名前空間 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 組み立て [Aspose.HTML](../../../)


