---
title: "ICSS2Properties.TextShadow"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは、要素のテキストに適用される影効果のカンマ区切りリストを受け取ります。影効果は指定された順序で適用され、互いに重ね合わせることがありますが、テキスト自体を覆うことは決してありません。影効果はボックスのサイズを変更せず、境界を超えて伸びることがあります。影効果のスタックレベルは要素自体と同じです。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

このプロパティは、要素のテキストに適用される影効果のカンマ区切りリストを受け取ります。影効果は指定された順序で適用され、互いに重ね合わせることがありますが、テキスト自体を覆うことは決してありません。影効果はボックスのサイズを変更せず、境界を超えて伸びることがあります。[stack level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) の影効果は要素自体と同じです。

各影効果は影のオフセットを指定する必要があり、オプションでぼかし半径と影の色を指定できます。

影のオフセットは、テキストからの距離を示す 2 つの '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' 値で指定されます。最初の長さの値はテキストの右側への水平距離を指定します。負の水平長さの値は影をテキストの左側に配置します。2 番目の長さの値はテキストの下側への垂直距離を指定します。負の垂直長さの値は影をテキストの上側に配置します。

ぼかし半径は、影のオフセットの後でオプションとして指定できます。ぼかし半径は、ぼかし効果の境界を示す長さの値です。ぼかし効果を計算する正確なアルゴリズムは指定されていません。

色の値は、影効果の前後にオプションで指定できます。その色の値は影効果の基礎として使用されます。色が指定されていない場合、['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) プロパティの値が代わりに使用されます。

```java
public String TextShadow { get; set; }
```

### 戻り値

text-shadow プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
