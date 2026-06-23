---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGGraphicsElement-metod. Returnerar transformationsmatrisen från aktuella användarenheter, d.v.s. efter tillämpning av transform-attributet om det finns, till förälderns enhet som uppfattar en pixel. För visningsenheter representerar detta idealiskt en fysisk skärm‑pixel. För andra enheter eller miljöer där fysiska pixelformat är okända kan en algoritm liknande CSS2‑definitionen av en pixel användas istället. Observera att null returneras om detta element inte är kopplat till dokumentträdet. Denna metod skulle ha kunnat heta getClientCTM, men namnet getScreenCTM behålls av historiska skäl."
type: docs

url: /sv/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Returnerar transformationsmatrisen från aktuella användarenheter (dvs. efter tillämpning av attributet ‘transform’, om någon) till den överordnade användaragents definition av en "pixel". För displayenheter representerar detta idealiskt en fysisk skärm‑pixel. För andra enheter eller miljöer där fysiska pixelformer inte är kända kan en algoritm liknande CSS2‑definitionen av en "pixel" användas istället. Observera att null returneras om detta element inte är kopplat till dokumentträdet. Denna metod skulle ha kunnat heta getClientCTM, men namnet getScreenCTM behålls av historiska skäl.

```java
public SVGMatrix GetScreenCTM()
```

### Returvärde

Ett SVGMatrix-objekt som definierar den givna transformationsmatrisen.

### Se även

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
