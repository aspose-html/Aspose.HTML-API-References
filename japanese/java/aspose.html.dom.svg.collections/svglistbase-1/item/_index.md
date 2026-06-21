---
title: "SVGListBase-1.Item"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGListBase プロパティ。リストのインデックス番目の項目を返します"
type: docs

url: /ja/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

リストのインデックス番目の項目を返します。

```java
public T this[ulong index] { get; set; }
```

| パラメータ | 説明 |
| --- | --- |
| index | リスト内のインデックス。 |

### 戻り値

リストのインデックス番目の位置に格納されているオブジェクト。

### Property Value

リストに格納されている項目の型。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/)。インデックス番号が numberOfItems 以上の場合に発生します。 |

### 関連項目

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
