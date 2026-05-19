---
title: "SVGMatrix クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.datatypes.SVGMatrix クラス。SVG の多くのグラフィック操作は、形式 a c e b d f の 2x3 行列を使用し、行列演算のために 3x3 行列に拡張すると a c e b d f 0 0 1 になります。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

SVG の多くのグラフィック操作は、次の形の 2x3 行列を使用します: [a c e] [b d f]。行列演算のために 3x3 行列に拡張すると、次のようになります: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | 行列の A 成分。 |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | 行列の B 成分。 |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | 行列の C 成分。 |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | 行列の D 成分。 |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | 行列の E 成分。 |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | 行列の F 成分。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドおよび（オプションで）マネージド リソースを解放します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | 行列の乗算を実行します。この行列は別の行列で後置乗算され、結果として新しい行列が返されます。 |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | 現在の行列に回転変換を後置乗算し、結果の行列を返します。 |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | 現在の行列に均一スケール変換を後置乗算し、結果の行列を返します。 |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | 現在の行列に非均一スケール変換を後置乗算し、結果の行列を返します。 |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | 現在の行列に skewX 変換を後置乗算し、結果の行列を返します。 |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | 現在の行列に skewY 変換を後置乗算し、結果の行列を返します。 |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | このインスタンスを表す文字列を返します。 |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | 現在の行列に平行移動変換を後置乗算し、結果の行列を返します。 |

### 関連項目

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
