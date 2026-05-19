---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGSVGElement プロパティ。最外層の svg 要素では、この属性はユーザーの拡大縮小やパン操作を考慮した、初期ビューに対する現在のスケール係数を示します（「拡大縮小とパン」の項で説明）。DOM 属性 currentScale と currentTranslate は 2x3 行列 a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y に相当します。拡大縮小が有効 (例: zoomAndPan=“magnify”) の場合、SVG ドキュメントフラグメントの最外層レベル、すなわち最外層 svg 要素の外側に余分な変換が適用されたかのようになります。最外層でない svg 要素でアクセスされた場合、この属性の動作は未定義です。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

最外層の svg 要素では、この属性はユーザーの拡大縮小やパン操作を考慮した、初期ビューに対する現在のスケール係数を示します（「拡大縮小とパン」の項で説明）。DOM 属性 currentScale と currentTranslate は 2x3 行列 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y] に相当します。"magnification" が有効 (例: zoomAndPan="magnify") の場合、SVG ドキュメントフラグメントの最外層レベル、すなわち最外層 svg 要素の外側に余分な変換が適用されたかのようになります。最外層でない ‘svg’ 要素でアクセスされた場合、この属性の動作は未定義です。

```java
public float CurrentScale { get; set; }
```

### Property Value

現在のスケール。

### 関連項目

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
