---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGListBase メソッド。リスト内の既存の項目を新しい項目に置き換えます"
type: docs

url: /ja/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

リスト内の既存の項目を新しい項目に置き換えます。

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| newItem | T | リストに挿入される項目。 |
| index | UInt64 | 置き換えられる項目のインデックスです。最初の項目は番号 0 です。 |

### 戻り値

挿入された項目。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/)。インデックス番号が numberOfItems 以上の場合に発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
