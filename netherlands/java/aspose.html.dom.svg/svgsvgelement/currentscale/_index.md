---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGSVGElement‑eigenschap. Op een buitenste svg‑element geeft dit attribuut de huidige schaalfactor weer ten opzichte van de initiële weergave, rekening houdend met gebruikersvergroting en pan‑operaties zoals beschreven onder Vergroting en pannen. DOM‑attributen currentScale en currentTranslate zijn equivalent aan de 2x3‑matrix a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Als vergroting is ingeschakeld, d.w.z. zoomAndPanmagnify, dan is het effect alsof er een extra transformatie op het buitenste niveau van het SVG‑documentfragment wordt geplaatst, d.w.z. buiten het buitenste svg‑element. Wanneer dit wordt benaderd op een svg‑element dat geen buitenste svg‑element is, is het gedrag van dit attribuut ongedefinieerd."
type: docs

url: /nl/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Op een buitenste svg‑element geeft dit attribuut de huidige schaalfactor weer ten opzichte van de initiële weergave, rekening houdend met gebruikersvergroting en pan‑operaties, zoals beschreven onder Vergroting en pannen. DOM‑attributen currentScale en currentTranslate zijn equivalent aan de 2x3‑matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Als "magnification" is ingeschakeld (d.w.z. zoomAndPan="magnify"), dan is het effect alsof er een extra transformatie op het buitenste niveau van het SVG‑documentfragment wordt geplaatst (d.w.z. buiten het buitenste svg‑element). Wanneer dit wordt benaderd op een ‘svg’-element dat geen buitenste svg‑element is, is het gedrag van dit attribuut ongedefinieerd.

```java
public float CurrentScale { get; set; }
```

### Property Value

De huidige schaal.

### Zie ook

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
