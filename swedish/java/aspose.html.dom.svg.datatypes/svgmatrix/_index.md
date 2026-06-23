---
title: "SVGMatrix-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.datatypes.SVGMatrix-klassen. Många av SVG:s grafikoperationer använder 2x3-matriser av formen a c e b d f som när de expanderas till en 3x3-matris för matrisaritmetik blir a c e b d f 0 0 1"
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Många av SVG:s grafikoperationer använder 2×3‑matriser av formen: [a c e] [b d f] som, när de expanderas till en 3×3‑matris för matrisaritmetik, blir: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | A-komponenten i matrisen. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | B-komponenten i matrisen. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | C-komponenten i matrisen. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | D-komponenten i matrisen. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | E-komponenten i matrisen. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | F-komponenten i matrisen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Utför matris-multiplikation. Denna matris post-multipliceras med en annan matris och returnerar den resulterande nya matrisen. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Post-multiplicerar en rotations-transformation på den aktuella matrisen och returnerar den resulterande matrisen. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Post-multiplicerar en enhetlig skalnings-transformation på den aktuella matrisen och returnerar den resulterande matrisen. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Post-multiplicerar en icke-enhetlig skalnings-transformation på den aktuella matrisen och returnerar den resulterande matrisen. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Postmultiplicerar en skewX‑transformation på den aktuella matrisen och returnerar den resulterande matrisen. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Postmultiplicerar en skewY‑transformation på den aktuella matrisen och returnerar den resulterande matrisen. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Returnerar en sträng som representerar detta objekt. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Postmultiplicerar en translations‑transformation på den aktuella matrisen och returnerar den resulterande matrisen. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
