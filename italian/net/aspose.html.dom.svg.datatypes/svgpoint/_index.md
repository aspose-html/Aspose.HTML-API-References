---
title: Class SVGPoint
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Svg.DataTypes.SVGPoint classe. Molte delle interfacce SVG DOM fanno riferimento a oggetti della classe SVGPoint. Un SVGPoint è una coppia di coordinate x y. Quando viene utilizzato nelle operazioni di matrice un SVGPoint viene trattato come un vettore della forma x y 1 Se un oggetto SVGRect è designato come di sola lettura il tentativo di assegnazione a uno dei suoi attributi comportare la generazione di uneccezione.
type: docs
weight: 1250
url: /it/net/aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

Molte delle interfacce SVG DOM fanno riferimento a oggetti della classe SVGPoint. Un SVGPoint è una coppia di coordinate (x, y). Quando viene utilizzato nelle operazioni di matrice, un SVGPoint viene trattato come un vettore della forma: [x] [y] [1] Se un oggetto SVGRect è designato come di sola lettura, il tentativo di assegnazione a uno dei suoi attributi comportare la generazione di un'eccezione.

```csharp
public class SVGPoint : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [X](../../aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | La coordinata X. |
| [Y](../../aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | La coordinata Y. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e, facoltativamente, gestite. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [MatrixTransform](../../aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Applica una trasformazione di matrice 2x3 su questo oggetto SVGPoint e restituisce un nuovo oggetto SVGPoint trasformato: newpoint = matrix* thispoint |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgpoint/tostring/)() | Restituisce aString che rappresenta questa istanza. |

### Guarda anche

* class [SVGValueType](../svgvaluetype/)
* spazio dei nomi [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* assemblea [Aspose.HTML](../../)


