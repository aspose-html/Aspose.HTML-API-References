---
title: Class SVGTransform
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform klas. SVGTransform is de interface voor een van de componenttransformaties binnen een SVGTransformList dus een SVGTransformobject komt overeen met een enkele component bijv. schaal... of matrix... binnen een transformattribuutspecificatie.
type: docs
weight: 1300
url: /nl/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform is de interface voor een van de componenttransformaties binnen een SVGTransformList; dus een SVGTransform-object komt overeen met een enkele component (bijv. 'schaal(...)' of 'matrix(...)') binnen een 'transform'-attribuutspecificatie.

```csharp
public class SVGTransform : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | Een gemakskenmerk voor SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY. Het bevat de opgegeven hoek. Voor SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE en SVG_TRANSFORM_SCALE is de hoek nul. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | De matrix die deze transformatie vertegenwoordigt. Het matrixobject is live, wat betekent dat eventuele wijzigingen in het SVGTransform-object onmiddellijk worden weergegeven in het matrixobject en vice versa. Als het matrixobject direct wordt gewijzigd (dwz zonder de methoden op de SVGTransform-interface zelf te gebruiken), verandert het type van de SVGTransform in SVG_TRANSFORM_MATRIX. Voor SVG_TRANSFORM_MATRIX bevat de matrix de a, b, c, d, e, f waarden geleverd door de gebruiker. Voor SVG_TRANSFORM_TRANSLATE vertegenwoordigen e en f de omzettingsbedragen (a= 1, b= 0, c= 0 en d = 1). Voor SVG_TRANSFORM_SCALE vertegenwoordigen a en d de schaalbedragen (b= 0 , c= 0, e= 0 en f = 0). Voor SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY vertegenwoordigen a, b, c en d de matrix die resulteert in de gegeven scheefheid (e= 0 en f = 0). Voor SVG_TRANSFORM_ROTATE , a, b, c, d, e en f vertegenwoordigen samen de matrix die zal resulteren in de gegeven rotatie. Wanneer de rotatie rond het middelpunt (0, 0) is, zullen e en f nul zijn. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | Het type waarde zoals gespecificeerd door een van de SVG_TRANSFORM_*-constanten die op deze interface zijn gedefinieerd. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Geeft onbeheerde en - optioneel - beheerde bronnen vrij. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Stelt het transformatietype in op SVG_TRANSFORM_MATRIX, waarbij de parametermatrix de nieuwe transformatie definieert. De waarden uit de parametermatrix worden gekopieerd, de matrixparameter vervangt niet SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Stelt het transformatietype in op SVG_TRANSFORM_ROTATE, waarbij parameter angle de rotatiehoek definieert en parameters cx en cy het optionele rotatiecentrum definiëren. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Stelt het transformatietype in op SVG_TRANSFORM_SCALE, met parameters sx en sy die de schaalbedragen definiëren. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Stelt het transformatietype in op SVG_TRANSFORM_SKEWX, waarbij de parameterhoek de hoeveelheid scheefheid definieert. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Stelt het transformatietype in op SVG_TRANSFORM_SKEWY, waarbij de parameter hoek de hoeveelheid scheefheid definieert. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Stelt het transformatietype in op SVG_TRANSFORM_TRANSLATE, met parameters tx en ty die de omzettingsbedragen definiëren. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Een 'matrix(...)'-transformatie. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Een transformatie 'draaien(...)'. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Een 'schaal(…)' transformatie. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Een 'skewX(...)'-transformatie. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Een 'skewY(…)' transformatie. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Een 'vertaal(…)' transformatie. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Het eenheidstype is niet een van de vooraf gedefinieerde typen. Het is ongeldig om te proberen een nieuwe waarde van dit type te definiëren of om een bestaande waarde naar dit type om te schakelen. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* naamruimte [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* montage [Aspose.HTML](../../)


