---
title: "HTMLTableRowElement.DeleteCell"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HTMLTableRowElement メソッド。現在の行からセルを削除します。"
type: docs

url: /ja/java/com.aspose.html/htmltablerowelement/deletecell/
---
## HTMLTableRowElement.DeleteCell method

現在の行からセルを削除します。

```java
public void DeleteCell(int index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 削除するセルのインデックス（0 から開始）。インデックスが -1 の場合、行の最後のセルが削除されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定された `index` がセル数以上であるか、-1 以外の負の数である場合に発生します。@version DOM Level 2 |

### 関連項目

* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
