---
title: SVGTransform.Matrix
second_title: Aspose.HTML för .NET API Referens
description: SVGTransform fast egendom. Matrisen som representerar denna transformation. Matrisobjektet är live vilket innebär att alla ändringar som görs i SVGTransformobjektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt dvs. utan att använda metoderna på själva SVGTransformgränssnittet ändras typen av SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen a b c d e f värden som tillhandahålls av användaren. För SVG_TRANSFORM_TRANSLATE representerar e och f översättningsbeloppena 1 b 0 c 0 och d  1. För SVG_TRANSFORM_SCALE representerar a och d skalbeloppenb 0  c 0 e 0 och f  0. För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a b c och d matrisen som kommer att resultera i den givna snedställningen e 0 och f  0. För SVG_TRANSFORM_ROTATE  a b c d e och f representerar tillsammans matrisen som kommer att resultera i den givna rotationen. När rotationen är runt mittpunkten 0 0 kommer e och f att vara noll.
type: docs
weight: 20
url: /sv/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Matrisen som representerar denna transformation. Matrisobjektet är live, vilket innebär att alla ändringar som görs i SVGTransform-objektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt (dvs. utan att använda metoderna på själva SVGTransform-gränssnittet) ändras typen av SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen a, b, c, d, e, f värden som tillhandahålls av användaren. För SVG_TRANSFORM_TRANSLATE representerar e och f översättningsbeloppen(a= 1, b= 0, c= 0 och d = 1). För SVG_TRANSFORM_SCALE representerar a och d skalbeloppen(b= 0) , c= 0, e= 0 och f = 0). För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a, b, c och d matrisen som kommer att resultera i den givna snedställningen (e= 0 och f = 0). För SVG_TRANSFORM_ROTATE , a, b, c, d, e och f representerar tillsammans matrisen som kommer att resultera i den givna rotationen. När rotationen är runt mittpunkten (0, 0), kommer e och f att vara noll.

```csharp
public SVGMatrix Matrix { get; }
```

### Fastighetsvärde

Matrisen som representerar denna transformation.

### Se även

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namnutrymme [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* hopsättning [Aspose.HTML](../../../)


