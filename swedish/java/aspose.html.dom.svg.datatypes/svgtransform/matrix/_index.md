---
title: "SVGTransform.Matrix"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGTransform-egenskap. Matrisen som representerar denna omvandling. Matrisobjektet är levande, vilket betyder att alla ändringar som görs på SVGTransform-objektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt, d.v.s. utan att använda metoderna på SVGTransform-gränssnittet själv, ändras typen på SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen a, b, c, d, e, f‑värdena som användaren har angett. För SVG_TRANSFORM_TRANSLATE representerar e och f translationsvärdena (a=1, b=0, c=0 och d=1). För SVG_TRANSFORM_SCALE representerar a och d skaleringsvärdena (b=0, c=0, e=0 och f=0). För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a, b, c och d matrisen som ger den angivna skevheten (e=0 och f=0). För SVG_TRANSFORM_ROTATE representerar a, b, c, d, e och f tillsammans matrisen som ger den angivna rotationen. När rotationen är kring centrumpunkten (0,0) kommer e och f att vara noll."
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Matrisen som representerar denna omvandling. Matrisobjektet är levande, vilket betyder att alla ändringar som görs på SVGTransform-objektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt (d.v.s. utan att använda metoderna på SVGTransform-gränssnittet själv) ändras typen på SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen a, b, c, d, e, f‑värdena som användaren har angett. För SVG_TRANSFORM_TRANSLATE representerar e och f translationsvärdena (a=1, b=0, c=0 och d=1). För SVG_TRANSFORM_SCALE representerar a och d skaleringsvärdena (b=0, c=0, e=0 och f=0). För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a, b, c och d matrisen som ger den angivna skevheten (e=0 och f=0). För SVG_TRANSFORM_ROTATE representerar a, b, c, d, e och f tillsammans matrisen som ger den angivna rotationen.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

Matrisen som representerar denna omvandling.

### Se även

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
