---
title: SVGTransform.Matrix
second_title: Справочник по Aspose.HTML для .NET API
description: SVGTransform свойство. Матрица представляющая это преобразование. Объект матрицы является активным что означает что любые изменения внесенные в объект SVGTransform немедленно отражаются в объекте матрицы и наоборот. В случае если объект матрицы изменяется напрямую т. е. без использования методов самого интерфейса SVGTransform то тип SVGTransform изменяется на SVG_TRANSFORM_MATRIX. Для SVG_TRANSFORM_MATRIX матрица содержит a b c d e f значения предоставленные пользователем. Для SVG_TRANSFORM_TRANSLATE e и f представляют суммы перевода a  1 b  0 c  0 и d  1. Для SVG_TRANSFORM_SCALE a и d представляют суммы шкалы b  0  c 0 e 0 и f  0. Для SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY a b c и d представляют матрицу которая приведет к заданному перекосу e 0 и f  0. Для SVG_TRANSFORM_ROTATE  a b c d e и f вместе представляют матрицу которая приведет к заданному вращению. Когда вращение происходит вокруг центральной точки 0 0 e и f будут равны нулю.
type: docs
weight: 20
url: /ru/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Матрица, представляющая это преобразование. Объект матрицы является активным, что означает, что любые изменения, внесенные в объект SVGTransform, немедленно отражаются в объекте матрицы и наоборот. В случае, если объект матрицы изменяется напрямую (т. е. без использования методов самого интерфейса SVGTransform), то тип SVGTransform изменяется на SVG_TRANSFORM_MATRIX. Для SVG_TRANSFORM_MATRIX матрица содержит a, b, c, d, e, f значения, предоставленные пользователем. Для SVG_TRANSFORM_TRANSLATE e и f представляют суммы перевода (a = 1, b = 0, c = 0 и d = 1). Для SVG_TRANSFORM_SCALE a и d представляют суммы шкалы (b = 0 , c= 0, e= 0 и f = 0). Для SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY a, b, c и d представляют матрицу, которая приведет к заданному перекосу (e= 0 и f = 0). Для SVG_TRANSFORM_ROTATE , a, b, c, d, e и f вместе представляют матрицу, которая приведет к заданному вращению. Когда вращение происходит вокруг центральной точки (0, 0), e и f будут равны нулю.

```csharp
public SVGMatrix Matrix { get; }
```

### Стоимость имущества

Матрица, представляющая это преобразование.

### Смотрите также

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* пространство имен [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* сборка [Aspose.HTML](../../../)


