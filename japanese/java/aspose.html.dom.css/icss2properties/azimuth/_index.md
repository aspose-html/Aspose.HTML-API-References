---
title: "ICSS2Properties.Azimuth"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。空間オーディオは聴覚プレゼンテーションにおける重要な様式的プロパティです。実際の生活で人々が部屋の同じ場所に全員が立つことはほとんどないように、複数の声を区別する自然な方法を提供します"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

空間オーディオは聴覚プレゼンテーションにおける重要な様式的プロパティです。実際の生活（人々が部屋の同じ場所に全員が立つことはほとんどない）で声を区別する自然な方法を提供します。

```java
public String Azimuth { get; set; }
```

### 戻り値

azimuth プロパティ

### Property Value

値は以下の意味を持ちます:

angle - 位置は '-360deg' から '360deg' の範囲の角度で記述されます。値 '0deg' はサウンドステージの中央で正面を意味します。'90deg' は右、'180deg' は背後、そして '270deg'（あるいは同等で便利な '-90deg'）は左を示します。

left-side - '270deg' と同じです。'behind' の場合は '270deg'。

far-left - '300deg' と同じです。'behind' の場合は '240deg'。

left - '320deg' と同じです。'behind' の場合は '220deg'。

center-left - '340deg' と同じです。'behind' の場合は '200deg'。

center - '0deg' と同じです。'behind' の場合は '180deg'。

center-right - '20deg' と同じです。'behind' の場合は '160deg'。

right - '40deg' と同じです。'behind' の場合は '140deg'。

far-right - '60deg' と同じです。'behind' の場合は '120deg'。

right-side - '90deg' と同じです。'behind' の場合は '90deg'。

leftwards - 現在の角度に対して音を左へ移動させます。正確には 20 度減算します。演算は 360 度での剰余として行われます。'leftwards' は実際には「反時計回りに回転した」ことを意味する方が正確です。常に 20 度減算するため、継承された azimuth がすでにリスナーの背後にある場合でも（その場合音は実際には右へ移動しているように見えます）。

rightwards - 現在の角度に対して音を右へ移動させます。正確には 20 度加算します。演算については 'leftwards' を参照してください。

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
