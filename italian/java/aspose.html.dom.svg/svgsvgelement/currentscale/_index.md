---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà SVGSVGElement. Su un elemento svg più esterno, questo attributo indica il fattore di scala corrente rispetto alla vista iniziale, tenendo conto dell'ingrandimento e delle operazioni di panoramica dell'utente, come descritto nella sezione Ingrandimento e panoramica. Gli attributi DOM currentScale e currentTranslate sono equivalenti alla matrice 2x3 a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Se l'ingrandimento è abilitato, cioè zoomAndPanmagnify, l'effetto è come se una trasformazione aggiuntiva fosse applicata al livello più esterno del frammento del documento SVG, cioè al di fuori dell'elemento svg più esterno. Quando viene accesso su un elemento svg che non è l'elemento svg più esterno, il comportamento di questo attributo è indefinito."
type: docs

url: /it/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Su un elemento svg più esterno, questo attributo indica il fattore di scala corrente rispetto alla vista iniziale, tenendo conto dell'ingrandimento e delle operazioni di panoramica dell'utente, come descritto nella sezione Ingrandimento e panoramica. Gli attributi DOM currentScale e currentTranslate sono equivalenti alla matrice 2x3 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Se "magnification" è abilitato (cioè, zoomAndPan="magnify"), l'effetto è come se una trasformazione aggiuntiva fosse applicata al livello più esterno del frammento del documento SVG (cioè, al di fuori dell'elemento svg più esterno). Quando viene accesso su un elemento ‘svg’ che non è un elemento svg più esterno, è indefinito quale comportamento abbia questo attributo.

```java
public float CurrentScale { get; set; }
```

### Property Value

La scala corrente.

### Vedi anche

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
