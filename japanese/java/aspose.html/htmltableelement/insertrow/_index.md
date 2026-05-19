---
title: "HTMLTableElement.InsertRow"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HTMLTableElement メソッド。テーブルに新しい空の行を挿入します。新しい行は、テーブル内の現在の index 番目の行の直前かつ同じセクションに挿入されます。index が -1 もしくは行数と同じ場合、新しい行は末尾に追加されます。さらに、テーブルが空の場合、行は作成されテーブルに挿入される TBODY に挿入されます。HTML 4.01 によれば、テーブル行は空にできません。"
type: docs

url: /ja/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

テーブルに新しい空行を挿入します。新しい行は、テーブル内の現在の `index` 番目の行の直前、同じセクションに挿入されます。`index` が -1 もしくは行数と同じ場合、新しい行は末尾に追加されます。さらに、テーブルが空の場合、行は作成されテーブルに挿入される `TBODY` に挿入されます。テーブル行は [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)] に従い空にできません。

```java
public Node InsertRow(int index)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| index | Int32 | 新しい行を挿入する行番号。このインデックスは 0 から始まり、テーブル内に含まれるすべての行の論理順序（文書順序ではなく）に対して相対的です。 |

### 戻り値

新しく作成された行です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定されたインデックスが行数より大きい場合、または -1 以外の負の数の場合に発生します。 @version DOM Level 2 |

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
