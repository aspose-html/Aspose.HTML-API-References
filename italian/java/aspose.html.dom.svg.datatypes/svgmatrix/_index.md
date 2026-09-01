---
title: "Classe SVGMatrix"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.dom.svg.datatypes.SVGMatrix. Molte delle operazioni grafiche SVG utilizzano matrici 2x3 della forma a c e b d f che, quando espanse in una matrice 3x3 per scopi di aritmetica matriciale, diventano a c e b d f 0 0 1"
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Molte delle operazioni grafiche di SVG utilizzano matrici 2x3 della forma: [a c e] [b d f] che, quando espanse in una matrice 3x3 ai fini dell'aritmetica matriciale, diventano: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | Il componente A della matrice. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | Il componente B della matrice. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | Il componente C della matrice. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | Il componente D della matrice. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | Il componente E della matrice. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | Il componente F della matrice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Esegue la moltiplicazione di matrici. Questa matrice è post-moltiplicata da un'altra matrice, restituendo la nuova matrice risultante. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Post-moltiplica una trasformazione di rotazione sulla matrice corrente e restituisce la matrice risultante. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Post-moltiplica una trasformazione di scala uniforme sulla matrice corrente e restituisce la matrice risultante. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Post-moltiplica una trasformazione di scala non uniforme sulla matrice corrente e restituisce la matrice risultante. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Moltiplica in post una trasformazione skewX sulla matrice corrente e restituisce la matrice risultante. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Moltiplica in post una trasformazione skewY sulla matrice corrente e restituisce la matrice risultante. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Restituisce una stringa che rappresenta questa istanza. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Moltiplica in post una trasformazione di traslazione sulla matrice corrente e restituisce la matrice risultante. |

### Vedi anche

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
