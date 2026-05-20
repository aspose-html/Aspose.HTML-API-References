---
title: "ISVGAnimatedPathData gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData gränssnitt. SVGAnimatedPathData‑gränssnittet stöder element som har ett d‑attribut som innehåller SVG‑sökvägsdata och möjliggör att animera det attributet."
type: docs

url: /sv/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData‑gränssnittet stöder element som har ett ‘d’-attribut som innehåller SVG‑sökvägsdata, och stödjer möjligheten att animera det attributet.

```java
public interface ISVGAnimatedPathData
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Ger åtkomst till det aktuella animerade innehållet i ‘d’-attributet i ett format som matchar SVG:s syntax en‑till‑en. Om det angivna attributet eller egenskapen är animerat, innehåller det det aktuella animerade värdet för attributet eller egenskapen, och både objektet självt och dess innehåll är skrivskyddade. Om det angivna attributet eller egenskapen för närvarande inte är animerat, innehåller det samma värde som pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Ger åtkomst till de grundläggande (dvs. statiska) innehållen i ‘d’-attributet i ett format som matchar SVG:s syntax en‑till‑en. Således, om ‘d’-attributet har ett "absolut moveto (M)" och ett "absolut arcto (A)"‑kommando, kommer pathSegList att innehålla två poster: en SVG_PATHSEG_MOVETO_ABS och en SVG_PATHSEG_ARC_ABS. |

### Se även

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
