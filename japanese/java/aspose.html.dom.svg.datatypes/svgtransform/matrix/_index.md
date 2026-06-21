---
title: "SVGTransform.Matrix"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGTransform プロパティ。この変換を表す行列です。行列オブジェクトはライブであり、SVGTransform オブジェクトに加えた変更は即座に行列オブジェクトに反映され、逆も同様です。行列オブジェクトが直接（SVGTransform インターフェイスのメソッドを使用せずに）変更された場合、SVGTransform のタイプは SVG_TRANSFORM_MATRIX に変わります。SVG_TRANSFORM_MATRIX の場合、行列はユーザーが指定した a、b、c、d、e、f の値を含みます。SVG_TRANSFORM_TRANSLATE の場合、e と f は平行移動量を表し、a=1、b=0、c=0、d=1 です。SVG_TRANSFORM_SCALE の場合、a と d はスケール量を表し、b=0、c=0、e=0、f=0 です。SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY の場合、a、b、c、d は指定されたスキューを実現する行列を表します（e=0、f=0）。SVG_TRANSFORM_ROTATE の場合、a、b、c、d、e、f が合わせて指定された回転を実現する行列を表します。回転の中心が (0, 0) の場合、e と f は 0 になります。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

この変換を表す行列です。行列オブジェクトはライブであり、SVGTransform オブジェクトへの変更は即座に行列オブジェクトに反映され、逆も同様です。行列オブジェクトが直接（SVGTransform インターフェイスのメソッドを使用せずに）変更された場合、SVGTransform のタイプは SVG_TRANSFORM_MATRIX に変わります。SVG_TRANSFORM_MATRIX では、行列はユーザーが指定した a、b、c、d、e、f の値を含みます。SVG_TRANSFORM_TRANSLATE では、e と f が平行移動量を表し、a=1、b=0、c=0、d=1 です。SVG_TRANSFORM_SCALE では、a と d がスケール量を表し、b=0、c=0、e=0、f=0 です。SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY では、a、b、c、d が指定されたスキューを実現する行列を表し（e=0、f=0）、SVG_TRANSFORM_ROTATE では、a、b、c、d、e、f が合わせて指定された回転を実現する行列を表します。回転の中心が (0, 0) の場合、e と f は 0 になります。

```java
public SVGMatrix Matrix { get; }
```

### Property Value

この変換を表す行列です。

### 関連項目

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
