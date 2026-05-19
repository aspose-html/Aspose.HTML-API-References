---
title: "SVGTransform.Matrix"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство SVGTransform. Матрица, представляющая эту трансформацию. Объект матрицы является живым, что означает, что любые изменения, внесённые в объект SVGTransform, немедленно отражаются в объекте матрицы и наоборот. Если объект матрицы изменяется напрямую, т.е. без использования методов интерфейса SVGTransform, тип SVGTransform меняется на SVG_TRANSFORM_MATRIX. Для SVG_TRANSFORM_MATRIX матрица содержит значения a, b, c, d, e, f, заданные пользователем. Для SVG_TRANSFORM_TRANSLATE e и f представляют величины трансляции (a=1, b=0, c=0 и d=1). Для SVG_TRANSFORM_SCALE a и d представляют величины масштабирования (b=0, c=0, e=0 и f=0). Для SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY a, b, c и d представляют матрицу, которая даст указанное искажение (e=0 и f=0). Для SVG_TRANSFORM_ROTATE a, b, c, d, e и f вместе представляют матрицу, которая даст указанное вращение. Когда вращение происходит вокруг центральной точки (0, 0), e и f будут равны нулю."
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Матрица, представляющая эту трансформацию. Объект матрицы является живым, что означает, что любые изменения, внесённые в объект SVGTransform, немедленно отражаются в объекте матрицы и наоборот. Если объект матрицы изменяется напрямую (т.е. без использования методов интерфейса SVGTransform), тип SVGTransform меняется на SVG_TRANSFORM_MATRIX. Для SVG_TRANSFORM_MATRIX матрица содержит значения a, b, c, d, e, f, заданные пользователем. Для SVG_TRANSFORM_TRANSLATE e и f представляют величины трансляции (a=1, b=0, c=0 и d=1). Для SVG_TRANSFORM_SCALE a и d представляют величины масштабирования (b=0, c=0, e=0 и f=0). Для SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY a, b, c и d представляют матрицу, которая даст указанное искажение (e=0 и f=0). Для SVG_TRANSFORM_ROTATE a, b, c, d, e и f вместе представляют матрицу, которая даст указанное вращение. Когда вращение происходит вокруг центральной точки (0, 0), e и f будут равны нулю.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

Матрица, представляющая эту трансформацию.

### См. также

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
