---
title: "SVGPoint Classe"
second_title: "Riferimento API Aspose.HTML per Java"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint class. Molte delle interfacce SVG DOM si riferiscono a oggetti della classe SVGPoint. Un SVGPoint è una coppia di coordinate x y. Quando viene usato in operazioni di matrice, un SVGPoint è trattato come un vettore della forma x y 1. Se un oggetto SVGRect è designato come sola lettura, allora tentare di assegnare a uno dei suoi attributi genererà un'eccezione."
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

Molte delle interfacce SVG DOM fanno riferimento a oggetti della classe SVGPoint. Un SVGPoint è una coppia di coordinate (x, y). Quando utilizzato in operazioni matriciali, un SVGPoint è trattato come un vettore della forma: [x] [y] [1] Se un oggetto SVGRect è designato come sola lettura, allora il tentativo di assegnare uno dei suoi attributi genererà un'eccezione.

```java
public class SVGPoint : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | La coordinata X. |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | La coordinata Y. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Applica una trasformazione matriciale 2x3 a questo oggetto SVGPoint e restituisce un nuovo oggetto SVGPoint trasformato: newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | Restituisce una String che rappresenta questa istanza. |

### Vedi anche

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
