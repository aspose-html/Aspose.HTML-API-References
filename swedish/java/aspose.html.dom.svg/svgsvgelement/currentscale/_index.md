---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGSVGElement‑egenskap. På ett yttersta svg‑element indikerar detta attribut den aktuella skalningsfaktorn i förhållande till den ursprungliga vyn för att ta hänsyn till användarmagnifiering och panorering, enligt avsnittet Magnification and panning. DOM‑attributen currentScale och currentTranslate motsvarar 2x3‑matrisen a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Om magnifiering är aktiverad, d.v.s. zoomAndPan=magnify, blir effekten som om en extra transformation placerades på den yttersta nivån i SVG‑dokumentfragmentet, dvs. utanför det yttersta svg‑elementet. När attributet läses på ett svg‑element som inte är det yttersta svg‑elementet är dess beteende odefinierat."
type: docs

url: /sv/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

På ett yttersta svg‑element indikerar detta attribut den aktuella skalningsfaktorn i förhållande till den ursprungliga vyn för att ta hänsyn till användarmagnifiering och panorering, enligt avsnittet Magnification and panning. DOM‑attributen currentScale och currentTranslate motsvarar 2x3‑matrisen [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Om \"magnification\" är aktiverat (d.v.s. zoomAndPan=\"magnify\"), blir effekten som om en extra transformation placerades på den yttersta nivån i SVG‑dokumentfragmentet (d.v.s. utanför det yttersta svg‑elementet). När attributet läses på ett ‘svg’-element som inte är det yttersta svg‑elementet är dess beteende odefinierat.

```java
public float CurrentScale { get; set; }
```

### Property Value

Den aktuella skalan.

### Se även

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
