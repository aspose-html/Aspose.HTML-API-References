---
title: Class SVGTransform
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform klas. SVGTransform ist die Schnittstelle für eine der Komponententransformationen innerhalb einer SVGTransformList daher entspricht ein SVGTransformObjekt einer einzelnen Komponente z. B. scale oder matrix innerhalb einer transformAttributspezifikation.
type: docs
weight: 1300
url: /de/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform ist die Schnittstelle für eine der Komponententransformationen innerhalb einer SVGTransformList; daher entspricht ein SVGTransform-Objekt einer einzelnen Komponente (z. B. „scale(…)“ oder „matrix(…)“) innerhalb einer „transform“-Attributspezifikation.

```csharp
public class SVGTransform : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | Ein praktisches Attribut für SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY. Es enthält den angegebenen Winkel. Für SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE und SVG_TRANSFORM_SCALE ist der Winkel Null. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | Die Matrix, die diese Transformation darstellt. Das Matrix-Objekt ist live, was bedeutet, dass alle am SVGTransform-Objekt vorgenommenen Änderungen sofort im Matrix-Objekt widergespiegelt werden und umgekehrt. Falls das Matrixobjekt direkt geändert wird (dh ohne die Methoden der SVGTransform-Schnittstelle selbst zu verwenden), ändert sich der Typ der SVGTransform zu SVG_TRANSFORM_MATRIX. Für SVG_TRANSFORM_MATRIX enthält die Matrix a, b, c, d, e, f vom Benutzer bereitgestellte Werte. Für SVG_TRANSFORM_TRANSLATE stellen e und f die Übersetzungsbeträge dar (a= 1, b= 0, c= 0 und d = 1). Für SVG_TRANSFORM_SCALE stellen a und d die Skalierungsbeträge dar (b= 0). , c= 0, e= 0 und f = 0). Für SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY stellen a, b, c und d die Matrix dar, die zu der gegebenen Verzerrung führt (e= 0 und f = 0). Für SVG_TRANSFORM_ROTATE , a, b, c, d, e und f stellen zusammen die Matrix dar, die zu der angegebenen Drehung führt. Wenn die Drehung um den Mittelpunkt (0, 0) erfolgt, sind e und f null. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | Der Typ des Werts, wie er von einer der auf dieser Schnittstelle definierten SVG_TRANSFORM_*-Konstanten angegeben wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Legt den Transformationstyp auf SVG_TRANSFORM_MATRIX fest, wobei die Parametermatrix die neue Transformation definiert. Die Werte aus der Parametermatrix werden kopiert, der Matrixparameter ersetzt nicht SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Legt den Transformationstyp auf SVG_TRANSFORM_ROTATE fest, wobei der Parameter angle den Rotationswinkel und die Parameter cx und cy das optionale Rotationszentrum definieren. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Legt den Transformationstyp auf SVG_TRANSFORM_SCALE fest, wobei die Parameter sx und sy die Skalierungsbeträge definieren. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Legt den Transformationstyp auf SVG_TRANSFORM_SKEWX fest, wobei der Parameter angle den Grad der Schräglage definiert. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Legt den Transformationstyp auf SVG_TRANSFORM_SKEWY fest, wobei der Parameter angle den Grad der Schräglage definiert. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Legt den Transformationstyp auf SVG_TRANSFORM_TRANSLATE fest, wobei die Parameter tx und ty die Übersetzungsbeträge definieren. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Eine „Matrix(…)“-Transformation. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Eine „rotate(…)“-Transformation. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Eine „Maßstab(…)“-Transformation. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Eine 'skewX(…)'-Transformation. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Eine 'skewY(…)'-Transformation. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Eine „Translate(…)“-Transformation. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Der Einheitentyp ist keiner der vordefinierten Typen. Es ist ungültig, einen neuen Wert dieses Typs zu definieren oder einen vorhandenen Wert auf diesen Typ umzustellen. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* namensraum [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* Montage [Aspose.HTML](../../)


