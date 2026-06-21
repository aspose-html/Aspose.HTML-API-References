---
title: "ICSSValueList.Item"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSSValueList プロパティ。このメソッドは順序インデックスで CSSValue を取得するために使用されます。このコレクション内の順序は CSS スタイルプロパティの値の順序を表します。インデックスがリスト内の値の数以上の場合は null を返します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

このメソッドは順序インデックスで CSSValue を取得するために使用されます。このコレクション内の順序は CSS スタイルプロパティの値の順序を表します。インデックスがリスト内の値の数以上の場合、null を返します。

こちらも参照してください [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### 戻り値

インデックス位置にある [`CSSValue`](../../cssvalue/) を、[`CSSValueList`](../../cssvaluelist/) から取得します。無効なインデックスの場合は null です。

### Property Value

コレクション内のインデックスです。

## 備考

この機能は元々 [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style) 仕様で定義されていましたが、その後の標準化の取り組みからは削除されています。

現在は標準化の道筋にある、モダンで互換性のない [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API) に取って代わられました。

### 関連項目

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
