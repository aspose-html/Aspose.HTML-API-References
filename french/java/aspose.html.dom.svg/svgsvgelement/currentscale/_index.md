---
title: "SVGSVGElement.CurrentScale"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété SVGSVGElement. Sur un élément svg le plus externe, cet attribut indique le facteur d'échelle actuel par rapport à la vue initiale afin de tenir compte du grossissement et du déplacement de l'utilisateur comme décrit dans Magnification and panning. Les attributs DOM currentScale et currentTranslate sont équivalents à la matrice 2x3 a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Si le grossissement est activé, c.-à-d. zoomAndPanmagnify, l'effet est comme si une transformation supplémentaire était placée au niveau le plus externe du fragment de document SVG, c.-à-d. à l'extérieur de l'élément svg le plus externe. Lorsqu'il est accédé sur un élément svg qui n'est pas le plus externe, le comportement de cet attribut est indéfini."
type: docs

url: /fr/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Sur un élément svg le plus externe, cet attribut indique le facteur d'échelle actuel par rapport à la vue initiale afin de tenir compte du grossissement et du déplacement de l'utilisateur, comme décrit dans Magnification and panning. Les attributs DOM currentScale et currentTranslate sont équivalents à la matrice 2x3 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Si "magnification" est activée (c.-à-d. zoomAndPan="magnify"), alors l'effet est comme si une transformation supplémentaire était placée au niveau le plus externe du fragment de document SVG (c.-à-d. à l'extérieur de l'élément svg le plus externe). Lorsqu'il est accédé sur un élément ‘svg’ qui n'est pas le plus externe, le comportement de cet attribut est indéfini.

```java
public float CurrentScale { get; set; }
```

### Property Value

L'échelle actuelle.

### Voir aussi

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
