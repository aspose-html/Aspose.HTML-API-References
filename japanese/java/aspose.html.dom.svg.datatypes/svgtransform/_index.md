---
title: "SVGTransform クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform クラス。SVGTransform は SVGTransformList 内のコンポーネント変換の一つのインターフェイスであり、SVGTransform オブジェクトは transform 属性指定内の単一コンポーネント（例: scale や matrix）に対応します"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform は SVGTransformList 内のコンポーネント変換の一つのインターフェイスです。そのため、SVGTransform オブジェクトは ‘transform’ 属性指定内の単一コンポーネント（例: 'scale(…)' や 'matrix(…)') に対応します。

```java
public class SVGTransform : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) SVG_TRANSFORM_ROTATE、SVG_TRANSFORM_SKEWX、SVG_TRANSFORM_SKEWY 用の便利な属性です。指定された角度を保持します。SVG_TRANSFORM_MATRIX、SVG_TRANSFORM_TRANSLATE、SVG_TRANSFORM_SCALE の場合、angle は 0 になります。 |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) この変換を表すマトリックスです。マトリックスオブジェクトはライブであり、SVGTransform オブジェクトへの変更は即座にマトリックスオブジェクトに反映され、逆も同様です。マトリックスオブジェクトが直接変更された場合（つまり、SVGTransform インターフェイスのメソッドを使用せずに）、SVGTransform のタイプは SVG_TRANSFORM_MATRIX に変わります。SVG_TRANSFORM_MATRIX の場合、マトリックスはユーザーが提供した a、b、c、d、e、f の値を含みます。SVG_TRANSFORM_TRANSLATE の場合、e と f は平行移動量を表します (a=1, b=0, c=0, d=1)。SVG_TRANSFORM_SCALE の場合、a と d はスケール量を表します (b=0, c=0, e=0, f=0)。SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY の場合、a、b、c、d は指定されたスキューを生み出すマトリックスを表します (e=0, f=0)。SVG_TRANSFORM_ROTATE の場合、a、b、c、d、e、f が合わせて指定された回転を生み出すマトリックスを表します。回転が中心点 (0,0) 周りの場合、e と f は 0 になります。 |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) このインターフェイスで定義された SVG_TRANSFORM_* 定数のいずれかによって指定された値のタイプです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドおよび（オプションで）マネージド リソースを解放します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | パラメータ matrix で新しい変換を定義し、変換タイプを SVG_TRANSFORM_MATRIX に設定します。パラメータ matrix の値はコピーされ、matrix パラメータは SVGTransform::matrix を置き換えません。 |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | パラメータ angle で回転角度を、パラメータ cx と cy でオプションの回転中心を定義し、変換タイプを SVG_TRANSFORM_ROTATE に設定します。 |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | パラメータ sx と sy でスケール量を定義し、変換タイプを SVG_TRANSFORM_SCALE に設定します。 |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | パラメータ angle でスキュー量を定義し、変換タイプを SVG_TRANSFORM_SKEWX に設定します。 |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | パラメータ angle でスキュー量を定義し、変換タイプを SVG_TRANSFORM_SKEWY に設定します。 |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | パラメータ tx と ty で平行移動量を定義し、変換タイプを SVG_TRANSFORM_TRANSLATE に設定します。 |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | このインスタンスを表す文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | 'matrix(…)' 変換です。 |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | 'rotate(…)' 変換です。 |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | 「scale(…)」変換。 |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | 「skewX(…)」変換。 |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | 「skewY(…)」変換。 |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | 「translate(…)」変換。 |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | ユニットタイプは事前定義されたタイプのいずれでもありません。このタイプの新しい値を定義しようとしたり、既存の値をこのタイプに切り替えようとすることは無効です。 |

### 関連項目

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
