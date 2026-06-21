---
title: "HTMLTableElement.DeleteRow"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HTMLTableElement メソッド。テーブル行を削除します"
type: docs

url: /ja/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

テーブル行を削除します。

```java
public void DeleteRow(int index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 削除する行のインデックスです。このインデックスは 0 から始まり、テーブル内に含まれるすべての行の論理順序（文書順序ではなく）に対して相対的です。インデックスが -1 の場合、テーブルの最後の行が削除されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: 指定されたインデックスが行数以上であるか、-1 以外の負の数である場合に発生します。 @version DOM Level 2 |

### 関連項目

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
