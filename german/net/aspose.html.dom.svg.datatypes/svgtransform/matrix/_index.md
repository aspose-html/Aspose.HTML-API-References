---
title: SVGTransform.Matrix
second_title: Aspose.HTML für .NET-API-Referenz
description: SVGTransform eigendom. Die Matrix die diese Transformation darstellt. Das MatrixObjekt ist live was bedeutet dass alle am SVGTransformObjekt vorgenommenen Änderungen sofort im MatrixObjekt widergespiegelt werden und umgekehrt. Falls das Matrixobjekt direkt geändert wird dh ohne die Methoden der SVGTransformSchnittstelle selbst zu verwenden ändert sich der Typ der SVGTransform zu SVG_TRANSFORM_MATRIX. Für SVG_TRANSFORM_MATRIX enthält die Matrix a b c d e f vom Benutzer bereitgestellte Werte. Für SVG_TRANSFORM_TRANSLATE stellen e und f die Übersetzungsbeträge dar a 1 b 0 c 0 und d  1. Für SVG_TRANSFORM_SCALE stellen a und d die Skalierungsbeträge dar b 0.  c 0 e 0 und f  0. Für SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY stellen a b c und d die Matrix dar die zu der gegebenen Verzerrung führt e 0 und f  0. Für SVG_TRANSFORM_ROTATE  a b c d e und f stellen zusammen die Matrix dar die zu der angegebenen Drehung führt. Wenn die Drehung um den Mittelpunkt 0 0 erfolgt sind e und f null.
type: docs
weight: 20
url: /de/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Die Matrix, die diese Transformation darstellt. Das Matrix-Objekt ist live, was bedeutet, dass alle am SVGTransform-Objekt vorgenommenen Änderungen sofort im Matrix-Objekt widergespiegelt werden und umgekehrt. Falls das Matrixobjekt direkt geändert wird (dh ohne die Methoden der SVGTransform-Schnittstelle selbst zu verwenden), ändert sich der Typ der SVGTransform zu SVG_TRANSFORM_MATRIX. Für SVG_TRANSFORM_MATRIX enthält die Matrix a, b, c, d, e, f vom Benutzer bereitgestellte Werte. Für SVG_TRANSFORM_TRANSLATE stellen e und f die Übersetzungsbeträge dar (a= 1, b= 0, c= 0 und d = 1). Für SVG_TRANSFORM_SCALE stellen a und d die Skalierungsbeträge dar (b= 0). , c= 0, e= 0 und f = 0). Für SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY stellen a, b, c und d die Matrix dar, die zu der gegebenen Verzerrung führt (e= 0 und f = 0). Für SVG_TRANSFORM_ROTATE , a, b, c, d, e und f stellen zusammen die Matrix dar, die zu der angegebenen Drehung führt. Wenn die Drehung um den Mittelpunkt (0, 0) erfolgt, sind e und f null.

```csharp
public SVGMatrix Matrix { get; }
```

### Eigentumswert

Die Matrix, die diese Transformation darstellt.

### Siehe auch

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namensraum [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* Montage [Aspose.HTML](../../../)


