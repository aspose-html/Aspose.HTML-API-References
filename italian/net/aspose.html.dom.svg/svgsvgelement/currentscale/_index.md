---
title: SVGSVGElement.CurrentScale
second_title: Aspose.HTML per riferimento API .NET
description: SVGSVGElement proprietà. Su un elemento svg più esterno questo attributo indica il fattore di scala corrente relativo alla vista iniziale per tenere conto delle operazioni di ingrandimento e panoramica dellutente come descritto in Ingrandimento e panoramica. Gli attributi DOM currentScale e currentTranslate sono equivalenti alla matrice 2x3 abcdef  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Se lingrandimento è abilitato ovvero zoomAndPanmagnify leffetto è come se una trasformazione extra fosse posizionata al livello più esterno del frammento del documento SVG ovvero allesterno dellelemento svg più esterno. Quando si accede il un elemento svg che non è un elemento svg più esterno non è definito quale comportamento abbia questo attributo.
type: docs
weight: 10
url: /it/net/aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Su un elemento svg più esterno, questo attributo indica il fattore di scala corrente relativo alla vista iniziale per tenere conto delle operazioni di ingrandimento e panoramica dell'utente, come descritto in Ingrandimento e panoramica. Gli attributi DOM currentScale e currentTranslate sono equivalenti alla matrice 2x3 [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Se l'"ingrandimento" è abilitato (ovvero zoomAndPan="magnify"), l'effetto è come se una trasformazione extra fosse posizionata al livello più esterno del frammento del documento SVG (ovvero, all'esterno dell'elemento svg più esterno). Quando si accede il un elemento 'svg' che non è un elemento svg più esterno, non è definito quale comportamento abbia questo attributo.

```csharp
public float CurrentScale { get; set; }
```

### Valore della proprietà

La scala corrente.

### Guarda anche

* class [SVGSVGElement](../)
* spazio dei nomi [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* assemblea [Aspose.HTML](../../../)


