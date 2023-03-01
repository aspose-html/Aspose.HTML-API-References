---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.HTML for .NET API リファレンス
description: SVGListBase 方法. リストの指定された位置に新しい項目を挿入します最初の項目は番号 0. です
type: docs
weight: 90
url: /ja/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

リストの指定された位置に新しい項目を挿入します。最初の項目は番号 0. です。

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newItem | T | リストに挿入されるアイテム。 |
| index | UInt64 | 新しいアイテムが挿入される前のアイテムのインデックス。最初の項目は番号 0 です。インデックスが 0 の場合、新しい項目がリストの先頭に挿入されます。インデックスが numberOfItems 以上の場合、新しい項目がリストの最後に追加されます。 |

### 戻り値

挿入されたアイテム。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). リストを変更できない場合に発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* 名前空間 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 組み立て [Aspose.HTML](../../../)


