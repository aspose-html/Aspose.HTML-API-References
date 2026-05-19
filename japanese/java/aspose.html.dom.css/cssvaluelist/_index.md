---
title: "CSSValueList クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.CSSValueList クラス。CSSValueList インターフェイスは、CSS 値の順序付けられたコレクションの抽象化を提供します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

CSSValueList インターフェイスは、CSS 値の順序付けられたコレクションの抽象化を提供します。

注: このインターフェイスは型付けされた CSS オブジェクトモデルを作成しようとした試みの一部でした。この試みは中止され、ほとんどのブラウザーは実装していません。

```java
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | `CSSValueList` クラスの新しいインスタンスを初期化します。 |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | `CSSValueList` クラスの新しいインスタンスを初期化します。 |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | `CSSValueList` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [cSSText](../../com.aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) インターフェイスの cssText プロパティは、現在の計算済み CSS プロパティ値を表します。 |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 値の型を定義するコードです。 |
| [getItem](../../com.aspose.html.dom.css/cssvaluelist/item/) CSSValueList インターフェイスの item() メソッドは、順序インデックスで CSSValue を取得するために使用されます。 |
| [getLength](../../com.aspose.html.dom.css/cssvaluelist/length/) CSSValueList インターフェイスの読み取り専用プロパティ length は、リスト内の CSSValue の数を表します。インデックスの有効な範囲は 0 から length-1 までです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| [getEnumerator](../../com.aspose.html.dom.css/cssvaluelist/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| [getPlatformType](../../com.aspose.html.dom.css/cssvaluelist/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | このインスタンスを表す文字列を返します。 |

### 関連項目

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
