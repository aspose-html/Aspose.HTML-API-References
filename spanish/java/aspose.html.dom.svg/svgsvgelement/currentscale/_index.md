---
title: "SVGSVGElement.CurrentScale"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad SVGSVGElement. En un elemento svg más externo este atributo indica el factor de escala actual relativo a la vista inicial, teniendo en cuenta la ampliación y operaciones de desplazamiento del usuario, como se describe en Amplificación y desplazamiento. Los atributos DOM currentScale y currentTranslate son equivalentes a la matriz 2x3 a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Si la ampliación está habilitada, p.ej. zoomAndPanmagnify, el efecto es como si se aplicara una transformación adicional en el nivel más externo del fragmento del documento SVG, es decir, fuera del elemento svg más externo. Cuando se accede a un elemento svg que no es el más externo, el comportamiento de este atributo es indefinido."
type: docs

url: /es/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

En un elemento svg más externo, este atributo indica el factor de escala actual relativo a la vista inicial, teniendo en cuenta la ampliación y operaciones de desplazamiento del usuario, como se describe en Amplificación y desplazamiento. Los atributos DOM currentScale y currentTranslate son equivalentes a la matriz 2x3 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Si "magnification" está habilitado (p.ej., zoomAndPan="magnify"), el efecto es como si se aplicara una transformación adicional en el nivel más externo del fragmento del documento SVG (es decir, fuera del elemento svg más externo). Cuando se accede a un elemento ‘svg’ que no es el más externo, es indefinido qué comportamiento tiene este atributo.

```java
public float CurrentScale { get; set; }
```

### Property Value

La escala actual.

### Ver también

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
