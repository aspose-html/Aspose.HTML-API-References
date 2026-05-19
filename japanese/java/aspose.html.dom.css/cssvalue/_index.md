---
title: "CSSValue クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.CSSValue クラス。単純または複合的な値を表します。CSSValue オブジェクトは CSS プロパティのコンテキスト内でのみ発生します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

単純または複合的な値を表します。CSSValue オブジェクトは CSS プロパティのコンテキスト内でのみ出現します。

```java
public abstract class CSSValue : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | `CSSValue` インターフェイスの cssText プロパティは現在の計算済み CSS プロパティ値を表します。 |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 値の型を定義するコードです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | このインスタンスを表す文字列を返します。 |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | この値はカスタム値です。 |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | この値は継承され、cssText には "inherit" が含まれます。 |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | この値はプリミティブ値であり、CSSValue インターフェイスのこのインスタンスに対してバインディング固有のキャストメソッドを使用することで、CSSPrimitiveValue インターフェイスのインスタンスを取得できます。 |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | この値は CSSValue のリストであり、CSSValueList インターフェイスのインスタンスは、この CSSValue インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用することで取得できます。 |

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
