---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGListBase メソッド。指定された位置に新しい項目をリストへ挿入します。最初の項目は番号 0 です"
type: docs

url: /ja/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

指定された位置に新しい項目をリストに挿入します。最初の項目は番号 0 です。

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| newItem | T | リストに挿入される項目。 |
| index | UInt64 | 新しい項目を挿入する前の項目のインデックスです。最初の項目は番号 0 です。インデックスが 0 の場合、新しい項目はリストの先頭に挿入されます。インデックスが numberOfItems 以上の場合、新しい項目はリストの末尾に追加されます。 |

### 戻り値

挿入された項目。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
