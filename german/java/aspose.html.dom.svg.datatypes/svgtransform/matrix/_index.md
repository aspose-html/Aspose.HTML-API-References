---
title: "SVGTransform.Matrix"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGTransform-Eigenschaft. Die Matrix, die diese Transformation darstellt. Das Matrixobjekt ist live, das bedeutet, dass alle Änderungen am SVGTransform-Objekt sofort im Matrixobjekt und umgekehrt reflektiert werden. Falls das Matrixobjekt direkt geändert wird, d.h. ohne die Methoden der SVGTransform-Schnittstelle zu verwenden, ändert sich der Typ von SVGTransform zu SVG_TRANSFORM_MATRIX. Für SVG_TRANSFORM_MATRIX enthält die Matrix die vom Benutzer angegebenen Werte a, b, c, d, e, f. Für SVG_TRANSFORM_TRANSLATE stellen e und f die Translationsbeträge dar (a=1, b=0, c=0 und d=1). Für SVG_TRANSFORM_SCALE stellen a und d die Skalierungsbeträge dar (b=0, c=0, e=0 und f=0). Für SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY stellen a, b, c und d die Matrix dar, die die gegebene Schrägstellung ergibt (e=0 und f=0). Für SVG_TRANSFORM_ROTATE stellen a, b, c, d, e und f zusammen die Matrix dar, die die gegebene Rotation ergibt. Wenn die Rotation um den Mittelpunkt (0,0) erfolgt, sind e und f null."
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Die Matrix, die diese Transformation darstellt. Das Matrixobjekt ist live, das bedeutet, dass alle Änderungen am SVGTransform-Objekt sofort im Matrixobjekt und umgekehrt reflektiert werden. Wird das Matrixobjekt direkt geändert (d.h. ohne die Methoden der SVGTransform-Schnittstelle zu verwenden), ändert sich der Typ von SVGTransform zu SVG_TRANSFORM_MATRIX. Für SVG_TRANSFORM_MATRIX enthält die Matrix die vom Benutzer angegebenen Werte a, b, c, d, e, f. Für SVG_TRANSFORM_TRANSLATE stellen e und f die Translationsbeträge dar (a=1, b=0, c=0 und d=1). Für SVG_TRANSFORM_SCALE stellen a und d die Skalierungsbeträge dar (b=0, c=0, e=0 und f=0). Für SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY stellen a, b, c und d die Matrix dar, die die angegebene Schrägstellung ergibt (e=0 und f=0). Für SVG_TRANSFORM_ROTATE stellen a, b, c, d, e und f zusammen die Matrix dar, die die angegebene Rotation ergibt. Wenn die Rotation um den Mittelpunkt (0,0) erfolgt, sind e und f null.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

Die Matrix, die diese Transformation darstellt.

### Siehe auch

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
