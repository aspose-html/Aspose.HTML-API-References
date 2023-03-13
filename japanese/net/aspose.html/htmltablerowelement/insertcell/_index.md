---
title: HTMLTableRowElement.InsertCell
second_title: Aspose.HTML for .NET API リファレンス
description: HTMLTableRowElement 方法. 空の挿入TDセルをこの行に追加します の場合索引1 またはセルの数に等しい場合新しい セルが追加されます
type: docs
weight: 100
url: /ja/net/aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

空の挿入`TD`セルをこの行に追加します。 の場合`索引`-1 またはセルの数に等しい場合、新しい セルが追加されます。

```csharp
public HTMLElement InsertCell(int index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| index | Int32 | 0 から始まる、セルを挿入する場所。 |

### 戻り値

新しく作成されたセル。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定された場合に発生します`索引` がセル数より大きいか、インデックスが -1. 以外の負の数の場合 @version DOM レベル 2 |

### 関連項目

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* 名前空間 [Aspose.Html](../../htmltablerowelement/)
* 組み立て [Aspose.HTML](../../../)


