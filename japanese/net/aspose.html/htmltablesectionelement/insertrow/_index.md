---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML for .NET API リファレンス
description: HTMLTableSectionElement 方法. このセクションに行を挿入します新しい行は現在の 直前に挿入されます索引このセクションの th 行 の場合索引1 またはこの セクションの行数に等しい場合新しい行が追加されます
type: docs
weight: 70
url: /ja/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

このセクションに行を挿入します。新しい行は、現在の 直前に挿入されます`索引`このセクションの th 行。 の場合`索引`-1 またはこの セクションの行数に等しい場合、新しい行が追加されます。

```csharp
public HTMLElement InsertRow(int index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| index | Int32 | 新しい行を挿入する行番号。このインデックス は 0 から始まり、テーブル内のすべての行ではなく、 このセクション内に含まれる行に対してのみ相対的です。 |

### 戻り値

新しく作成された行。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定されたインデックスが 行数より大きい場合、インデックスが -1 以外の負数の場合に発生します。 @version DOM レベル 2 |

### 関連項目

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* 名前空間 [Aspose.Html](../../htmltablesectionelement/)
* 組み立て [Aspose.HTML](../../../)


