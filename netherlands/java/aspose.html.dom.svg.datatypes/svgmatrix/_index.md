---
title: "SVGMatrix klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.datatypes.SVGMatrix klasse. Veel van de grafische bewerkingen van SVG's gebruiken 2x3-matrices van de vorm a c e b d f die, wanneer ze worden uitgebreid tot een 3x3-matrix voor matrixrekenkunde, worden a c e b d f 0 0 1"
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Veel van de grafische bewerkingen van SVG gebruiken 2x3-matrices van de vorm: [a c e] [b d f] die, wanneer uitgebreid tot een 3x3-matrix voor matrixrekenkunde, worden: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | Het A‑component van de matrix. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | Het B‑component van de matrix. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | Het C‑component van de matrix. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | Het D‑component van de matrix. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | Het E‑component van de matrix. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | Het F‑component van de matrix. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft onbeheerste en - optioneel - beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Voert matrixvermenigvuldiging uit. Deze matrix wordt postvermenigvuldigd met een andere matrix, waarbij de resulterende nieuwe matrix wordt geretourneerd. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Postvermenigvuldigt een rotatie‑transformatie op de huidige matrix en retourneert de resulterende matrix. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Postvermenigvuldigt een uniforme schaaltransformatie op de huidige matrix en retourneert de resulterende matrix. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Postvermenigvuldigt een niet‑uniforme schaaltransformatie op de huidige matrix en retourneert de resulterende matrix. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Voegt post-multiplicatief een skewX-transformatie toe aan de huidige matrix en retourneert de resulterende matrix. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Voegt post-multiplicatief een skewY-transformatie toe aan de huidige matrix en retourneert de resulterende matrix. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Retourneert een String die deze instantie vertegenwoordigt. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Voegt post-multiplicatief een translatie-transformatie toe aan de huidige matrix en retourneert de resulterende matrix. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
