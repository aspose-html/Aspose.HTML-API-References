---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGGraphicsElement メソッド。現在のユーザー単位（すなわち、transform 属性が適用された後）から、親ユーザーエージェントが認識するピクセルへの変換行列を返します。ディスプレイデバイスでは理想的に物理的な画面ピクセルを表します。物理ピクセルサイズが不明な他のデバイスや環境では、CSS2 のピクセル定義に類似したアルゴリズムが使用されます。要素が文書ツリーに接続されていない場合は null が返されることに注意してください。このメソッドは本来 getClientCTM と名付ける方が適切ですが、歴史的理由により getScreenCTM という名前が維持されています。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

現在のユーザー単位（つまり、存在する場合は ‘transform’ 属性が適用された後）から親ユーザーエージェントが認識する「ピクセル」への変換行列を返します。表示デバイスの場合、理想的には物理的な画面ピクセルを表します。物理的なピクセルサイズが不明な他のデバイスや環境では、CSS2 の「ピクセル」定義に類似したアルゴリズムが代わりに使用できます。要素がドキュメントツリーに接続されていない場合は null が返されることに注意してください。このメソッドは本来 getClientCTM と名付けるべきでしたが、歴史的理由で getScreenCTM という名前が維持されています。

```java
public SVGMatrix GetScreenCTM()
```

### 戻り値

指定された変換行列を定義する SVGMatrix オブジェクトです。

### 関連項目

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
