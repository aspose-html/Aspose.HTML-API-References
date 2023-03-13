---
title: HTMLTableElement.DeleteRow
second_title: Aspose.HTML for .NET API リファレンス
description: HTMLTableElement 方法. テーブル行を削除します
type: docs
weight: 190
url: /ja/net/aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

テーブル行を削除します。

```csharp
public void DeleteRow(int index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| index | Int32 | 削除する行のインデックス。このインデックスは 0 から を開始し、テーブル内に含まれるすべての行の の論理的な順序 (ドキュメントの順序ではない) に相対的です。インデックスが -1 の場合、テーブルの 最後の行が削除されます。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定されたインデックスが行数より大きいか、 に等しい場合、またはインデックスが -1. 以外の負の数 である場合に発生します。 @version DOM レベル 2 |

### 関連項目

* class [HTMLTableElement](../)
* 名前空間 [Aspose.Html](../../htmltableelement/)
* 組み立て [Aspose.HTML](../../../)


