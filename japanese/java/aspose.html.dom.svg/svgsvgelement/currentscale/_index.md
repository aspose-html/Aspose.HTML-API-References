---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGSVGElement のプロパティです。最外層の svg 要素では、この属性はユーザーの拡大縮小やパン操作（「Magnification and panning」で説明）を考慮した、初期ビューに対する現在のスケール係数を示します。DOM 属性 currentScale と currentTranslate は、2x3 行列 a b c d e f = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y] と同等です。拡大縮小が有効 (例: zoomAndPan=\"magnify\") の場合、SVG ドキュメントフラグメントの最外層レベル、すなわち最外層 svg 要素の外側に余分な変換が適用されたかのように動作します。最外層でない svg 要素でこの属性にアクセスした場合、その動作は未定義です。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

最外層の svg 要素では、この属性はユーザーの拡大縮小やパン操作（「Magnification and panning」で説明）を考慮した、初期ビューに対する現在のスケール係数を示します。DOM 属性 currentScale と currentTranslate は、2x3 行列 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y] と同等です。"magnification" が有効 (例: zoomAndPan="magnify") の場合、SVG ドキュメントフラグメントの最外層、すなわち最外層 svg 要素の外側に余分な変換が適用されたかのように動作します。最外層でない ‘svg’ 要素でこの属性にアクセスした場合、その動作は未定義です。

```java
public float CurrentScale { get; set; }
```

### Property Value

現在のスケールです。

### 関連項目

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
