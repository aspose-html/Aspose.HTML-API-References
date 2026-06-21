---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGListBase メソッド。リストから既存の項目を削除します"
type: docs

url: /ja/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

リストから既存の項目を削除します。

```java
public T RemoveItem(ulong index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | UInt64 | 削除される項目のインデックス。最初の項目は番号 0 です。 |

### 戻り値

削除された項目。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/)。インデックス番号が numberOfItems 以上の場合に発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
