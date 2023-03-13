---
title: SVGTransform.Matrix
second_title: Aspose.HTML for .NET API リファレンス
description: SVGTransform 財産. この変換を表すマトリックスマトリックス オブジェクトはライブですつまりSVGTransform オブジェクトに加えられた変更はすぐにマトリックス オブジェクトに反映されその逆も同様ですマトリックス オブジェクトが直接変更された場合 つまりSVGTransform インターフェイス自体のメソッドを使用せずにSVGTransform の型は SVG_TRANSFORM_MATRIX. に変更されます SVG_TRANSFORM_MATRIX の場合マトリックスには abcdef が含まれますユーザーが指定した値. SVG_TRANSFORM_TRANSLATE の場合e と f は移動量を表します a 1b 0c 0 と d  1. SVG_TRANSFORM_SCALE の場合a と d はスケール量を表します b 0 c 0e 0 および f  0. SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY の場合abcおよび d は指定されたスキュー e 0 および f  0 になる行列を表します SVG_TRANSFORM_ROTATE の場合abcdeおよび f は一緒に指定された回転をもたらす行列を表します回転が中心点 0 0 の周りにある場合e および f はゼロになります
type: docs
weight: 20
url: /ja/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

この変換を表すマトリックス。マトリックス オブジェクトはライブです。つまり、SVGTransform オブジェクトに加えられた変更はすぐにマトリックス オブジェクトに反映され、その逆も同様です。マトリックス オブジェクトが直接変更された場合 (つまり、SVGTransform インターフェイス自体のメソッドを使用せずに)、SVGTransform の型は SVG_TRANSFORM_MATRIX. に変更されます。 SVG_TRANSFORM_MATRIX の場合、マトリックスには a、b、c、d、e、f が含まれます。ユーザーが指定した値. SVG_TRANSFORM_TRANSLATE の場合、e と f は移動量を表します (a= 1、b= 0、c= 0 と d = 1). SVG_TRANSFORM_SCALE の場合、a と d はスケール量を表します (b= 0 、c= 0、e= 0 および f = 0). SVG_TRANSFORM_SKEWX および SVG_TRANSFORM_SKEWY の場合、a、b、c、および d は、指定されたスキュー (e= 0 および f = 0) になる行列を表します。 SVG_TRANSFORM_ROTATE の場合、a、b、c、d、e、および f は一緒に、指定された回転をもたらす行列を表します。回転が中心点 (0, 0) の周りにある場合、e および f はゼロになります。

```csharp
public SVGMatrix Matrix { get; }
```

### プロパティ値

この変換を表す行列.

### 関連項目

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* 名前空間 [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* 組み立て [Aspose.HTML](../../../)


