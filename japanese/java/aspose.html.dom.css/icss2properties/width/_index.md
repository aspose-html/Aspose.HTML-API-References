---
title: "ICSS2Properties.Width"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは、ブロックレベル要素と置換要素によって生成されるボックスのコンテンツ幅を指定します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

このプロパティは、ブロックレベル要素と [replaced](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) 要素によって生成されるボックスの [content width](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) を指定します。

このプロパティは、置換されていない [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) 要素には適用されません。置換されていないインライン要素のボックスの幅は、子要素の相対オフセットがある前の、内部にレンダリングされたコンテンツの幅と同じです。インラインボックスは [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box) に流れることを思い出してください。ラインボックスの幅はそれらの [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) によって決まりますが、[floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats) の存在により短くなることがあります。

置換要素のボックスの幅は [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) であり、このプロパティの値が 'auto' と異なる場合、ユーザーエージェントによって拡大縮小されることがあります。

値は以下の意味を持ちます：

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - 固定幅を指定します。'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - パーセンテージ幅を指定します。パーセンテージは生成されたボックスの [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) の幅に対して計算されます。auto - 幅は他のプロパティの値に依存します。以下のセクションを参照してください。注: ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) の負の値は違法です。

```java
public String Width { get; set; }
```

### 戻り値

width プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
