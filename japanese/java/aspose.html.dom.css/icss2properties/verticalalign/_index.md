---
title: "ICSS2Properties.VerticalAlign"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは、インラインレベル要素によって生成されたボックスのラインボックス内での垂直位置に影響します。以下の値は、親インラインレベル要素、またはその要素が匿名インラインボックスを生成する場合の親ブロックレベル要素に対してのみ意味を持ち、該当する親が存在しない場合は効果がありません"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

このプロパティは、インラインレベル要素によって生成されたボックスのラインボックス内での垂直位置に影響します。以下の値は、親インラインレベル要素、またはその要素が[anonymous inline boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous) を生成する場合の親ブロックレベル要素に対してのみ意味を持ち、該当する親が存在しない場合は効果がありません。

注: このプロパティの値は、テーブルのコンテキストでは若干異なる意味を持ちます。詳細は[table height algorithms](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) のセクションを参照してください。baseline - ボックスのベースラインを親ボックスのベースラインに合わせます。ボックスにベースラインがない場合は、ボックスの下端を親のベースラインに合わせます。middle - ボックスの垂直中心点を親ボックスのベースライン＋親の x-height の半分に合わせます。sub - ボックスのベースラインを、親ボックスの下付き文字の適切な位置に下げます。（この値は要素のテキストのフォントサイズには影響しません。）super - ボックスのベースラインを、親ボックスの上付き文字の適切な位置に上げます。（この値は要素のテキストのフォントサイズには影響しません。）text-top - ボックスの上端を親要素のフォントの上端に合わせます。text-bottom - ボックスの下端を親要素のフォントの下端に合わせます。'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - 正の値でボックスを上げ、負の値で下げます（距離は ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height) の値のパーセンテージ）。値 '0%' は 'baseline' と同等です。'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - 正の値でボックスを上げ、負の値で下げます。値 '0cm' は 'baseline' と同等です。top - ボックスの上端を行ボックスの上端に合わせます。bottom - ボックスの下端を行ボックスの下端に合わせます。

```java
public String VerticalAlign { get; set; }
```

### 戻り値

vertical-align プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
