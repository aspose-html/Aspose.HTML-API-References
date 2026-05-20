---
title: "SVGTransform-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform-klass. SVGTransform är gränssnittet för en av komponenttransformeringarna inom en SVGTransformList, så ett SVGTransform-objekt motsvarar en enskild komponent, t.ex. skala eller matris inom en transformattributspecifikation"
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform är gränssnittet för en av komponenttransformationerna inom en SVGTransformList; således motsvarar ett SVGTransform‑objekt en enskild komponent (t.ex. 'scale(…)' eller 'matrix(…)') inom en ‘transform’-attributspecifikation.

```java
public class SVGTransform : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Ett bekvämt attribut för SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY. Det innehåller den specificerade vinkeln. För SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE och SVG_TRANSFORM_SCALE kommer vinkeln att vara noll. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) Matrisen som representerar denna transformation. Matrisobjektet är levande, vilket betyder att alla ändringar som görs på SVGTransform-objektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt (dvs. utan att använda metoderna på SVGTransform‑gränssnittet) ändras typen på SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen a, b, c, d, e, f‑värdena som tillhandahållits av användaren. För SVG_TRANSFORM_TRANSLATE representerar e och f translationsmängderna (a=1, b=0, c=0 och d=1). För SVG_TRANSFORM_SCALE representerar a och d skalningsmängderna (b=0, c=0, e=0 och f=0). För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a, b, c och d matrisen som ger den angivna skevningen (e=0 och f=0). För SVG_TRANSFORM_ROTATE representerar a, b, c, d, e och f tillsammans matrisen som ger den angivna rotationen. När rotationen är kring centrumpunkten (0, 0) blir e och f noll. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) Typen av värdet enligt en av SVG_TRANSFORM_*‑konstanterna som definieras på detta gränssnitt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Ställer in transformationstypen till SVG_TRANSFORM_MATRIX, med parametern matrix som definierar den nya transformationen. Värdena från parameter‑matrixen kopieras, matrix‑parametern ersätter inte SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Ställer in transformationstypen till SVG_TRANSFORM_ROTATE, med parametern angle som definierar rotationsvinkeln och parametrarna cx och cy som definierar det valfria rotationscentrumet. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Ställer in transformationstypen till SVG_TRANSFORM_SCALE, med parametrarna sx och sy som definierar skalningsmängderna. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Ställer in transformationstypen till SVG_TRANSFORM_SKEWX, med parametern angle som definierar mängden skevning. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Ställer in transformationstypen till SVG_TRANSFORM_SKEWY, med parametern angle som definierar mängden skevning. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Ställer in transformationstypen till SVG_TRANSFORM_TRANSLATE, med parametrarna tx och ty som definierar translationsmängderna. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Returnerar en sträng som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | En 'matrix(…)'‑transformation. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | En 'rotate(…)'‑transformation. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | En 'scale(…)' transformation. |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | En 'skewX(…)' transformation. |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | En 'skewY(…)' transformation. |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | En 'translate(…)' transformation. |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Enhetstypen är inte en av de fördefinierade typerna. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka byta ett befintligt värde till denna typ. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
