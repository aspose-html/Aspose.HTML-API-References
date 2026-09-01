---
title: "SVGMatrix-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.datatypes.SVGMatrix Klasse. Viele der SVG-Grafikoperationen verwenden 2x3-Matrizen der Form a c e b d f, die bei Erweiterung zu einer 3x3-Matrix für matrixarithmetische Zwecke zu a c e b d f 0 0 1 werden."
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Viele der Grafikoperationen von SVG verwenden 2x3-Matrizen der Form: [a c e] [b d f], die bei Erweiterung zu einer 3x3-Matrix für matrixarithmetische Zwecke werden: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | Die A-Komponente der Matrix. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | Die B-Komponente der Matrix. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | Die C-Komponente der Matrix. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | Die D-Komponente der Matrix. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | Die E-Komponente der Matrix. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | Die F-Komponente der Matrix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und - optional - verwaltete Ressourcen frei. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Führt Matrixmultiplikation durch. Diese Matrix wird post-multipliziert mit einer anderen Matrix, wobei die resultierende neue Matrix zurückgegeben wird. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Post-multipliziert eine Rotations­transformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Post-multipliziert eine einheitliche Skalierungstransformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Post-multipliziert eine nicht‑einheitliche Skalierungstransformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Post-multipliziert eine skewX-Transformation mit der aktuellen Matrix und gibt die resultierende Matrix zurück. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Post-multipliziert eine skewY-Transformation mit der aktuellen Matrix und gibt die resultierende Matrix zurück. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Post-multipliziert eine Translations-Transformation mit der aktuellen Matrix und gibt die resultierende Matrix zurück. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
