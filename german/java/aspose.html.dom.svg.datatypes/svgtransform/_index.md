---
title: "SVGTransform Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform Klasse. SVGTransform ist die Schnittstelle für eine der Komponenten‑Transformationen innerhalb einer SVGTransformList, sodass ein SVGTransform‑Objekt einer einzelnen Komponente entspricht, z. B. Skalierung oder Matrix, innerhalb einer Transform‑Attributspezifikation"
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform ist das Interface für eine der Komponenten-Transformationen innerhalb einer SVGTransformList; ein SVGTransform-Objekt entspricht also einer einzelnen Komponente (z. B. 'scale(…)' oder 'matrix(…)') innerhalb einer ‘transform’-Attributspezifikation.

```java
public class SVGTransform : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Ein bequemes Attribut für SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY. Es enthält den angegebenen Winkel. Für SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE und SVG_TRANSFORM_SCALE ist der Winkel null. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) Die Matrix, die diese Transformation darstellt. Das Matrix‑Objekt ist live, das heißt, alle Änderungen am SVGTransform‑Objekt werden sofort im Matrix‑Objekt und umgekehrt widergespiegelt. Wird das Matrix‑Objekt direkt geändert (d. h. ohne die Methoden der SVGTransform‑Schnittstelle zu verwenden), ändert sich der Typ des SVGTransform zu SVG_TRANSFORM_MATRIX. Für SVG_TRANSFORM_MATRIX enthält die Matrix die vom Benutzer angegebenen Werte a, b, c, d, e, f. Für SVG_TRANSFORM_TRANSLATE repräsentieren e und f die Translationsbeträge (a=1, b=0, c=0 und d=1). Für SVG_TRANSFORM_SCALE repräsentieren a und d die Skalierungsbeträge (b=0, c=0, e=0 und f=0). Für SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY repräsentieren a, b, c und d die Matrix, die die angegebene Schrägstellung erzeugt (e=0 und f=0). Für SVG_TRANSFORM_ROTATE repräsentieren a, b, c, d, e und f zusammen die Matrix, die die angegebene Drehung erzeugt. Wenn die Drehung um den Mittelpunkt (0, 0) erfolgt, sind e und f null. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) Der Typ des Wertes, wie durch eine der auf dieser Schnittstelle definierten SVG_TRANSFORM_*‑Konstanten angegeben. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und - optional - verwaltete Ressourcen frei. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Setzt den Transformationstyp auf SVG_TRANSFORM_MATRIX, wobei der Parameter matrix die neue Transformation definiert. Die Werte aus dem Parameter matrix werden kopiert, der Matrix‑Parameter ersetzt nicht SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Setzt den Transformationstyp auf SVG_TRANSFORM_ROTATE, wobei der Parameter angle den Rotationswinkel definiert und die Parameter cx und cy das optionale Rotationszentrum festlegen. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Setzt den Transformationstyp auf SVG_TRANSFORM_SCALE, wobei die Parameter sx und sy die Skalierungsbeträge festlegen. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Setzt den Transformationstyp auf SVG_TRANSFORM_SKEWX, wobei der Parameter angle die Schrägstellung definiert. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Setzt den Transformationstyp auf SVG_TRANSFORM_SKEWY, wobei der Parameter angle die Schrägstellung definiert. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Setzt den Transformationstyp auf SVG_TRANSFORM_TRANSLATE, wobei die Parameter tx und ty die Translationsbeträge festlegen. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Eine 'matrix(…)'‑Transformation. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Eine 'rotate(…)'‑Transformation. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Eine 'scale(…)'-Transformation. |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Eine 'skewX(…)'-Transformation. |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Eine 'skewY(…)'-Transformation. |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Eine 'translate(…)'-Transformation. |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Der Einheitstyp ist keiner der vordefinierten Typen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
