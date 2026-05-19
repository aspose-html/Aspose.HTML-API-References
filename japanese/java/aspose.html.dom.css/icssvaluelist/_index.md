---
title: "ICSSValueList インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSValueList インターフェイス。CSSValueList インターフェイスは CSSValue インターフェイスから派生し、CSS 値の順序付けられたコレクションの抽象化を提供します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

CSSValueList インターフェイスは [`CSSValue`](../cssvalue/) インターフェイスから派生し、CSS 値の順序付けられたコレクションの抽象化を提供します。

一部のプロパティは構文上空のリストを許可します。その場合、これらのプロパティは none 識別子を取ります。したがって、空のリストはプロパティの値が none であることを意味します。

CSSValueList の項目は整数インデックスでアクセスでき、0 から始まります。

```java
public interface ICSSValueList
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) このメソッドは序数インデックスで CSSValue を取得するために使用されます。このコレクション内の順序は CSS スタイルプロパティの値の順序を表します。インデックスがリスト内の値の数以上の場合、null を返します。 |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) CSSValueList インターフェイスの length 読み取り専用プロパティは、リスト内の CSSValue の数を表します。インデックスの有効な範囲は 0 から length‑1 まで（両端含む）です。 |

## Remarks

このインターフェイスは型付けされた CSS Object Model を作成しようとした試みの一部でしたが、その試みは中止され、ほとんどのブラウザーは実装していません。

目的を達成するには、次のものを使用できます：

型なしの [CSS Object Model](https://drafts.csswg.org/cssom/)（広くサポート）または、最新の [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects)（サポートは限定的で実験的と見なされます）。

### 関連項目

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
