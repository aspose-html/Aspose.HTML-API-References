---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGListBase メソッド。リストから指定された項目を返します"
type: docs

url: /ja/java/com.aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

リストから指定された項目を返します。

```java
public T GetItem(ulong index)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| index | UInt64 | 返されるリスト内の項目のインデックス。最初の項目は番号 0 です。 |

### 戻り値

選択された項目。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/)。インデックス番号が numberOfItems 以上の場合に発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
