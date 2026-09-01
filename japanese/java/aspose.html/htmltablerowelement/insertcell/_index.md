---
title: "HTMLTableRowElement.InsertCell"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HTMLTableRowElement メソッド。空の TD セルをこの行に挿入します。`index` が -1 またはセル数と等しい場合、新しいセルは末尾に追加されます"
type: docs

url: /ja/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

この行に空の `TD` セルを挿入します。`index` が -1 もしくはセル数と同じ場合、新しいセルは末尾に追加されます。

```java
public HTMLElement InsertCell(int index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | セルを挿入する位置です。0 から開始します。 |

### 戻り値

新しく作成されたセルです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定された `index` がセル数より大きい場合、または -1 以外の負の数の場合に発生します。@version DOM Level 2 |

### 関連項目

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
