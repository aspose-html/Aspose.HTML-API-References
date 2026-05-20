---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGGraphicsElement‑metod. Returnerar transformationsmatrisen från aktuella användarenheter, d.v.s. efter tillämpning av attributet transform, om något, på föräldra‑användarens uppfattning av en pixel. För visningsenheter representerar detta idealiskt en fysisk skärm‑pixel. För andra enheter eller miljöer där fysiska pixeldimensioner inte är kända kan istället en algoritm liknande CSS2‑definitionen av en pixel användas. Observera att null returneras om detta element inte är kopplat till dokumentträdet. Denna metod hade kunnat heta getClientCTM, men namnet getScreenCTM behålls av historiska skäl."
type: docs

url: /sv/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Returnerar transformationsmatrisen från aktuella användarenheter (dvs. efter tillämpning av attributet ‘transform’, om det finns) till den överordnade användaragenterens definition av en \"pixel\". För displayenheter representerar detta idealiskt en fysisk skärm‑pixel. För andra enheter eller miljöer där fysiska pixelstorlekar inte är kända kan en algoritm liknande CSS2‑definitionen av en \"pixel\" användas istället. Observera att null returneras om detta element inte är kopplat till dokumentträdet. Denna metod skulle ha kunnat heta getClientCTM, men namnet getScreenCTM behålls av historiska skäl.

```java
public SVGMatrix GetScreenCTM()
```

### Returvärde

Ett SVGMatrix‑objekt som definierar den angivna transformationsmatrisen.

### Se även

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
