---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HTMLTableSectionElement メソッド。このセクションに行を挿入します。新しい行はこのセクションの現在の index 番目の行の直前に挿入されます。index が -1 またはこのセクションの行数と等しい場合、新しい行は末尾に追加されます。"
type: docs

url: /ja/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

このセクションに行を挿入します。新しい行はこのセクションの現在の `index` 番目の行の直前に挿入されます。`index` が -1 またはこのセクションの行数と等しい場合、新しい行は末尾に追加されます。

```java
public HTMLElement InsertRow(int index)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| index | Int32 | 新しい行を挿入する行番号。このインデックスは 0 から始まり、このセクション内に含まれる行に対してのみ相対的であり、テーブル全体の行には適用されません。 |

### 戻り値

新しく作成された行です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定されたインデックスが行数より大きい場合、または -1 以外の負の数の場合に発生します。@version DOM Level 2 |

### 関連項目

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
