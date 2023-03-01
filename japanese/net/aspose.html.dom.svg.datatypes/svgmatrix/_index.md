---
title: Class SVGMatrix
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Svg.DataTypes.SVGMatrix クラス. SVG のグラフィック操作の多くは ace bdf の形式の 2x3 行列を使用します行列演算のために 3x3 行列に展開すると ace bdf 0 0 1
type: docs
weight: 1220
url: /ja/net/aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

SVG のグラフィック操作の多くは、 [ace] [bdf] の形式の 2x3 行列を使用します。行列演算のために 3x3 行列に展開すると、 [ace] [bdf] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | 行列の A コンポーネント。 |
| [B](../../aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | マトリックスの B コンポーネント。 |
| [C](../../aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | 行列の C コンポーネント。 |
| [D](../../aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | 行列の D コンポーネント。 |
| [E](../../aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | 行列の E コンポーネント。 |
| [F](../../aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | 行列の F コンポーネント。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 管理されていないリソースと、オプションで管理されているリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [Multiply](../../aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | 行列の乗算を実行します。この行列は別の行列で事後乗算され、結果の新しい行列が返されます. |
| [Rotate](../../aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | 現在の行列に回転変換を後置乗算し、結果の行列を返します。 |
| [Scale](../../aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | 現在の行列に均一なスケール変換を後置乗算し、結果の行列を返します. |
| [ScaleNonUniform](../../aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | 現在の行列に対して不均一なスケール変換を事後乗算し、結果の行列を返します. |
| [SkewX](../../aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | 現在の行列にskewX変換を後置乗算し、結果の行列を返します. |
| [SkewY](../../aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | 現在の行列に対して、skewY 変換を事後乗算し、結果の行列を返します。 |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgmatrix/tostring/)() | を返しますStringこのインスタンスを表す. |
| [Translate](../../aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | 現在の行列に並進変換を後置乗算し、結果の行列を返します。 |

### 関連項目

* class [SVGValueType](../svgvaluetype/)
* 名前空間 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 組み立て [Aspose.HTML](../../)


