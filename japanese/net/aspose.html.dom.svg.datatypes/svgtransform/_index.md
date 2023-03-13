---
title: Class SVGTransform
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform クラス. SVGTransform はSVGTransformList 内のコンポーネント変換の 1 つのインターフェイスですしたがってSVGTransform オブジェクトはtransform 属性仕様内の単一のコンポーネント 例えばscale または matrix に対応します
type: docs
weight: 1300
url: /ja/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform は、SVGTransformList 内のコンポーネント変換の 1 つのインターフェイスです。したがって、SVGTransform オブジェクトは、'transform' 属性仕様内の単一のコンポーネント (例えば、'scale(…)' または 'matrix(…)') に対応します。

```csharp
public class SVGTransform : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | SVG_TRANSFORM_ROTATE、SVG_TRANSFORM_SKEWX、および SVG_TRANSFORM_SKEWY の便利な属性。指定された角度を保持します。 SVG_TRANSFORM_MATRIX、SVG_TRANSFORM_TRANSLATE、および SVG_TRANSFORM_SCALE の場合、角度はゼロになります。 |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | この変換を表すマトリックス。マトリックス オブジェクトはライブです。つまり、SVGTransform オブジェクトに加えられた変更はすぐにマトリックス オブジェクトに反映され、その逆も同様です。マトリックス オブジェクトが直接変更された場合 (つまり、SVGTransform インターフェイス自体のメソッドを使用せずに)、SVGTransform の型は SVG_TRANSFORM_MATRIX. に変更されます。 SVG_TRANSFORM_MATRIX の場合、マトリックスには a、b、c、d、e、f が含まれます。ユーザーが指定した値. SVG_TRANSFORM_TRANSLATE の場合、e と f は移動量を表します (a= 1、b= 0、c= 0 と d = 1). SVG_TRANSFORM_SCALE の場合、a と d はスケール量を表します (b= 0 、c= 0、e= 0 および f = 0). SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY の場合、a、b、c、および d は、指定されたスキュー (e= 0 および f = 0) になる行列を表します。 SVG_TRANSFORM_ROTATE の場合、a、b、c、d、e、および f は一緒に、指定された回転をもたらす行列を表します。回転が中心点 (0, 0) の周りにある場合、e および f はゼロになります。 |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | このインターフェイスで定義された SVG_TRANSFORM_* 定数の 1 つによって指定された値の型。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 管理されていないリソースと、オプションで管理されているリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | 変換タイプを SVG_TRANSFORM_MATRIX に設定し、新しい変換を定義するパラメーター マトリックスを使用します。パラメーター マトリックスの値がコピーされます。マトリックス パラメーターは SVGTransform::matrix. を置き換えません。 |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | 変換タイプを SVG_TRANSFORM_ROTATE に設定します。パラメーター angle は回転角度を定義し、パラメーター cx および cy はオプションの回転中心を定義します。 |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | 変換タイプを SVG_TRANSFORM_SCALE に設定し、パラメーター sx および sy でスケール量を定義します。 |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | 変換タイプを SVG_TRANSFORM_SKEWX に設定し、パラメーター angle でスキューの量を定義します。 |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | 変換タイプを SVG_TRANSFORM_SKEWY に設定し、パラメーター angle でスキューの量を定義します。 |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | 変換タイプを SVG_TRANSFORM_TRANSLATE に設定し、パラメータ tx および ty で変換量を定義します。 |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | 「行列(…)」変換. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | 「回転(…)」変換. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | 'scale(…)' 変換. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | 'skewX(…)' 変換. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | 'skewY(…)' 変換. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | 'translate(…)' 変換. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | ユニット タイプが事前定義されたタイプの 1 つではありません。この型の新しい値を定義しようとしたり、既存の値をこの型に切り替えようとしたりすることは無効です. |

### 関連項目

* class [SVGValueType](../svgvaluetype/)
* 名前空間 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 組み立て [Aspose.HTML](../../)


