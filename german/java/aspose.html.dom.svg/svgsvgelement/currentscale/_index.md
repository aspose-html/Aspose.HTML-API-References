---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGSVGElement-Eigenschaft. Bei einem äußersten svg-Element gibt dieses Attribut den aktuellen Skalierungsfaktor relativ zur Ausgangsansicht an, um die Benutzervergrößerung und Schwenkoperationen zu berücksichtigen, wie unter Vergrößerung und Schwenken beschrieben. Die DOM-Attribute currentScale und currentTranslate entsprechen der 2x3-Matrix a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Wenn Vergrößerung aktiviert ist, d.h. zoomAndPanmagnify, wirkt es, als ob eine zusätzliche Transformation auf der äußersten Ebene des SVG-Dokumentfragments platziert wäre, also außerhalb des äußersten svg-Elements. Wird das Attribut auf einem svg-Element verwendet, das nicht das äußerste svg-Element ist, ist das Verhalten dieses Attributs nicht definiert."
type: docs

url: /de/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Bei einem äußersten svg-Element gibt dieses Attribut den aktuellen Skalierungsfaktor relativ zur Ausgangsansicht an, um die Benutzervergrößerung und Schwenkoperationen zu berücksichtigen, wie unter Vergrößerung und Schwenken beschrieben. Die DOM-Attribute currentScale und currentTranslate entsprechen der 2x3-Matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Wenn "magnification" aktiviert ist (d.h. zoomAndPan="magnify"), wirkt es, als ob eine zusätzliche Transformation auf der äußersten Ebene des SVG-Dokumentfragments (d.h. außerhalb des äußersten svg-Elements) platziert wäre. Wird das Attribut auf einem ‘svg’-Element verwendet, das nicht das äußerste svg-Element ist, ist das Verhalten dieses Attributs nicht definiert.

```java
public float CurrentScale { get; set; }
```

### Property Value

Der aktuelle Maßstab.

### Siehe auch

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
