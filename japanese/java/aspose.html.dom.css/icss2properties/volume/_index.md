---
title: "ICSS2Properties.Volume"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。Volume は波形の中央値の音量を指します。つまり、音量が 50 の高度に抑揚のある声はそれ以上にピークになる可能性があります。全体の値は快適さのために人間が調整できることが想定されており、例えば物理的な音量コントロールで 0 と 100 の値が比例して増加するように設定できます。このプロパティが行うことはダイナミックレンジを調整することです"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/volume/
---
## ICSS2Properties.Volume property

Volume は波形の中央値の音量を指します。つまり、音量が 50 の高度に抑揚のある声はそれ以上にピークになる可能性があります。全体の値は快適さのために人間が調整できると考えられ、例えば物理的な音量コントロール（0 と 100 の値が比例して増加します）で調整できます。このプロパティが行うことはダイナミックレンジを調整することです。

値は以下の意味を持ちます:

‘[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)’ - ‘0’ から ‘100’ の間の任意の数です。‘0’ は最小の可聴音量レベルを表し、100 は最大の快適レベルに対応します。‘[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)’ - パーセンテージ値は継承された値に対して相対的に計算され、‘0’ から ‘100’ の範囲にクリップされます。silent - 完全に無音です。値 ‘0’ は ‘silent’ と同じ意味ではありません。x-soft - ‘0’ と同じです。soft - ‘25’ と同じです。medium - ‘50’ と同じです。loud - ‘75’ と同じです。x-loud - ‘100’ と同じです。

```java
public String Volume { get; set; }
```

### 戻り値

volume プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
