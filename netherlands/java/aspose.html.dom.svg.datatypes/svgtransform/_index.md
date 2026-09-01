---
title: "SVGTransform Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform klasse. SVGTransform is de interface voor een van de componenttransformaties binnen een SVGTransformList, zodat een SVGTransform‑object overeenkomt met een enkele component, bijv. schaal of matrix binnen een transform‑attribuut specificatie"
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform is de interface voor een van de componenttransformaties binnen een SVGTransformList; dus komt een SVGTransform-object overeen met een enkele component (bijv. 'scale(…)' of 'matrix(…)') binnen een ‘transform’-attribuutspecificatie.

```java
public class SVGTransform : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Een handig attribuut voor SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY. Het bevat de opgegeven hoek. Voor SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE en SVG_TRANSFORM_SCALE zal de hoek nul zijn. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) De matrix die deze transformatie vertegenwoordigt. Het matrix‑object is live, wat betekent dat alle wijzigingen die aan het SVGTransform‑object worden aangebracht onmiddellijk worden weerspiegeld in het matrix‑object en omgekeerd. Als het matrix‑object direct wordt gewijzigd (d.w.z. zonder de methoden op de SVGTransform‑interface zelf te gebruiken), verandert het type van de SVGTransform naar SVG_TRANSFORM_MATRIX. Voor SVG_TRANSFORM_MATRIX bevat de matrix de a, b, c, d, e, f waarden die door de gebruiker zijn opgegeven. Voor SVG_TRANSFORM_TRANSLATE vertegenwoordigen e en f de translatiewaarden (a= 1, b= 0, c= 0 en d = 1). Voor SVG_TRANSFORM_SCALE vertegenwoordigen a en d de schaalwaarden (b= 0, c= 0, e= 0 en f = 0). Voor SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY vertegenwoordigen a, b, c en d de matrix die resulteert in de opgegeven scheefstand (e= 0 en f = 0). Voor SVG_TRANSFORM_ROTATE vertegenwoordigen a, b, c, d, e en f samen de matrix die resulteert in de opgegeven rotatie. Wanneer de rotatie rond het middelpunt (0, 0) plaatsvindt, zullen e en f nul zijn. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) Het type van de waarde zoals gespecificeerd door een van de SVG_TRANSFORM_* constanten die op deze interface zijn gedefinieerd. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft niet-beheerde en - optioneel - beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Stelt het transformatietype in op SVG_TRANSFORM_MATRIX, met parameter matrix die de nieuwe transformatie definieert. De waarden van de matrix‑parameter worden gekopieerd; de matrix‑parameter vervangt SVGTransform::matrix niet. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Stelt het transformatietype in op SVG_TRANSFORM_ROTATE, met parameter angle die de rotatiehoek definieert en parameters cx en cy die het optionele rotatie‑centrum definiëren. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Stelt het transformatietype in op SVG_TRANSFORM_SCALE, met parameters sx en sy die de schaalwaarden definiëren. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Stelt het transformatietype in op SVG_TRANSFORM_SKEWX, met parameter angle die de mate van scheefstand definieert. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Stelt het transformatietype in op SVG_TRANSFORM_SKEWY, met parameter angle die de mate van scheefstand definieert. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Stelt het transformatietype in op SVG_TRANSFORM_TRANSLATE, met parameters tx en ty die de translatiewaarden definiëren. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Retourneert een String die dit exemplaar vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Een 'matrix(…)' transformatie. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Een 'rotate(…)' transformatie. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Een 'scale(…)' transformatie. |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Een 'skewX(…)' transformatie. |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Een 'skewY(…)' transformatie. |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Een 'translate(…)' transformatie. |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Het eenheidstype is niet een van de vooraf gedefinieerde typen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om te proberen een bestaande waarde naar dit type te wijzigen. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
