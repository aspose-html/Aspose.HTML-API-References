---
title: SVGListBase1.ReplaceItem
second_title: Aspose.HTML for .NET API リファレンス
description: SVGListBase 方法. リスト内の既存のアイテムを新しいアイテムに置き換えます
type: docs
weight: 110
url: /ja/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

リスト内の既存のアイテムを新しいアイテムに置き換えます。

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newItem | T | リストに挿入されるアイテム。 |
| index | UInt64 | 置換するアイテムのインデックス。最初の項目は番号 0 です。 |

### 戻り値

挿入されたアイテム。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). リストを変更できない場合に発生します。 |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). インデックス番号が numberOfItems 以上の場合に発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* 名前空間 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 組み立て [Aspose.HTML](../../../)


