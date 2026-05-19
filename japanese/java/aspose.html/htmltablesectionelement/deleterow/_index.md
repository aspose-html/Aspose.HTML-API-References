---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HTMLTableSectionElement メソッド。このセクションから行を削除します"
type: docs

url: /ja/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

このセクションから行を削除します。

```java
public void DeleteRow(int index)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| index | Int32 | 削除する行のインデックス、または最後の行を削除する場合は -1。このインデックスは 0 から始まり、このセクション内に含まれる行に対してのみ相対的であり、テーブル全体の行には適用されません。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定されたインデックスが行数以上であるか、-1 以外の負の数である場合に発生します。 @version DOM Level 2 |

### 関連項目

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
