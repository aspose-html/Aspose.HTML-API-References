---
title: Class SVGTransform
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform klass. SVGTransform är gränssnittet för en av komponenttransformationerna inom en SVGTransformList sålunda motsvarar ett SVGTransformobjekt en enskild komponent t.ex. scale... eller matrix... inom en transformattributspecifikation.
type: docs
weight: 1300
url: /sv/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform är gränssnittet för en av komponenttransformationerna inom en SVGTransformList; sålunda motsvarar ett SVGTransform-objekt en enskild komponent (t.ex. 'scale(...)' eller 'matrix(...)') inom en 'transform'-attributspecifikation.

```csharp
public class SVGTransform : SVGValueType
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | Ett bekvämlighetsattribut för SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY. Den innehåller vinkeln som specificerades. För SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE och SVG_TRANSFORM_SCALE kommer vinkeln att vara noll. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | Matrisen som representerar denna transformation. Matrisobjektet är live, vilket innebär att alla ändringar som görs i SVGTransform-objektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt (dvs. utan att använda metoderna på själva SVGTransform-gränssnittet) ändras typen av SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen a, b, c, d, e, f värden som tillhandahålls av användaren. För SVG_TRANSFORM_TRANSLATE representerar e och f översättningsbeloppen(a= 1, b= 0, c= 0 och d = 1). För SVG_TRANSFORM_SCALE representerar a och d skalbeloppen(b= 0) , c= 0, e= 0 och f = 0). För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a, b, c och d matrisen som kommer att resultera i den givna snedställningen (e= 0 och f = 0). För SVG_TRANSFORM_ROTATE , a, b, c, d, e och f representerar tillsammans matrisen som kommer att resultera i den givna rotationen. När rotationen är runt mittpunkten (0, 0), kommer e och f att vara noll. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | Typen av värdet som specificeras av en av SVG_TRANSFORM_*-konstanterna som definieras i detta gränssnitt. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Ställer in transformeringstypen till SVG_TRANSFORM_MATRIX, med parametermatrisen som definierar den nya transformationen. Värdena från parametermatrisen kopieras, matrisparametern ersätter inte SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Ställer in transformeringstypen till SVG_TRANSFORM_ROTATE, med parametervinkeln som definierar rotationsvinkeln och parametrarna cx och cy definierar det valfria rotationscentrumet. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Ställer in transformeringstypen till SVG_TRANSFORM_SCALE, med parametrarna sx och sy som definierar skalbeloppen. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Ställer in transformeringstypen till SVG_TRANSFORM_SKEWX, med parametervinkeln som definierar mängden skevhet. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Ställer in transformeringstypen till SVG_TRANSFORM_SKEWY, med parametervinkeln som definierar mängden skevhet. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Ställer in transformeringstypen till SVG_TRANSFORM_TRANSLATE, med parametrarna tx och ty som definierar översättningsbeloppen. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | En 'matris(...)'-transformation. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | En 'rotera(...)'-transformation. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | En 'scale(…)'-transformation. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | En 'skewX(…)'-transformation. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | En 'skewY(…)'-transformation. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | En 'translate(…)'-transformation. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Enhetstypen är inte en av fördefinierade typer. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka ändra ett befintligt värde till denna typ. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* namnutrymme [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* hopsättning [Aspose.HTML](../../)


