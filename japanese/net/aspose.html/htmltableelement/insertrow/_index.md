---
title: HTMLTableElement.InsertRow
second_title: Aspose.HTML for .NET API リファレンス
description: HTMLTableElement 方法. テーブルに新しい空の行を挿入します新しい行は現在の の直前の同じセクションに 挿入されます索引表の th 行もしも索引1 または が行数に等しい場合新しい行が追加されますさらに テーブルが空の場合行がTBODY が作成されテーブルに挿入されますHTML4.01 
type: docs
weight: 220
url: /ja/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

テーブルに新しい空の行を挿入します。新しい行は、現在の の直前の同じセクションに 挿入されます。`索引`表の th 行。もしも`索引`-1 または が行数に等しい場合、新しい行が追加されます。さらに、 テーブルが空の場合、行が`TBODY` が作成され、テーブルに挿入されます。[[HTML4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ]。

```csharp
public Node InsertRow(int index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| index | Int32 | 新しい行を挿入する行番号。このインデックス は 0 から始まり、テーブル内に含まれるすべての行の論理順序 (ドキュメント 順序ではない) に関連しています。 |

### 戻り値

新しく作成された行。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定されたインデックスが 行数より大きい場合、またはインデックスが -1. 以外の負の数である場合に発生します。 @version DOM レベル 2 |

### 関連項目

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* 名前空間 [Aspose.Html](../../htmltableelement/)
* 組み立て [Aspose.HTML](../../../)


