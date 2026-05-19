---
title: "ICSSValueList.Item"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSSValueList プロパティ。このメソッドは序数インデックスで CSSValue を取得するために使用されます。このコレクション内の順序は CSS スタイルプロパティの値の順序を表します。インデックスがリスト内の値の数以上の場合は null を返します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

このメソッドは、順序インデックスによって CSSValue を取得するために使用されます。このコレクション内の順序は、CSS スタイルプロパティの値の順序を表します。インデックスがリスト内の値の数以上の場合、null を返します。

以下も参照してください [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### 戻り値

インデックス位置にある [`CSSValue`](../../cssvalue/) は、[`CSSValueList`](../../cssvaluelist/) 内のもので、無効なインデックスの場合は null です。

### Property Value

コレクション内のインデックスです。

## Remarks

この機能は元々 [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style) 仕様で定義されていましたが、その後標準化の取り組みからは除外されました。

現在は標準化の道を進んでいる、モダンでありながら互換性のない [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API) に取って代わられました。

### 関連項目

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
