---
title: "SVGTransform.Matrix"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGTransform property. De matrix die deze transformatie vertegenwoordigt. Het matrixobject is live, wat betekent dat elke wijziging aan het SVGTransform-object onmiddellijk wordt weerspiegeld in het matrixobject en omgekeerd. Als het matrixobject direct wordt gewijzigd, d.w.z. zonder gebruik te maken van de methoden op de SVGTransform-interface zelf, verandert het type van de SVGTransform naar SVG_TRANSFORM_MATRIX. Voor SVG_TRANSFORM_MATRIX bevat de matrix de a b c d e f waarden die door de gebruiker zijn opgegeven. Voor SVG_TRANSFORM_TRANSLATE vertegenwoordigen e en f de translatiehoeveelheden a= 1 b= 0 c= 0 en d= 1. Voor SVG_TRANSFORM_SCALE vertegenwoordigen a en d de schaalhoeveelheden b= 0 c= 0 e= 0 en f= 0. Voor SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY vertegenwoordigen a b c en d de matrix die zal resulteren in de opgegeven scheefstand e= 0 en f= 0. Voor SVG_TRANSFORM_ROTATE vertegenwoordigen a b c d e en f samen de matrix die zal resulteren in de opgegeven rotatie. Wanneer de rotatie rond het middelpunt (0, 0) is, zullen e en f nul zijn."
type: docs

url: /nl/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

De matrix die deze transformatie vertegenwoordigt. Het matrixobject is live, wat betekent dat elke wijziging aan het SVGTransform-object onmiddellijk wordt weerspiegeld in het matrixobject en omgekeerd. Als het matrixobject direct wordt gewijzigd (d.w.z. zonder gebruik te maken van de methoden op de SVGTransform-interface zelf), verandert het type van de SVGTransform naar SVG_TRANSFORM_MATRIX. Voor SVG_TRANSFORM_MATRIX bevat de matrix de a, b, c, d, e, f waarden die door de gebruiker zijn opgegeven. Voor SVG_TRANSFORM_TRANSLATE vertegenwoordigen e en f de translatiehoeveelheden (a= 1, b= 0, c= 0 en d = 1). Voor SVG_TRANSFORM_SCALE vertegenwoordigen a en d de schaalhoeveelheden (b= 0, c= 0, e= 0 en f = 0). Voor SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY vertegenwoordigen a, b, c en d de matrix die zal resulteren in de opgegeven scheefstand (e= 0 en f = 0). Voor SVG_TRANSFORM_ROTATE vertegenwoordigen a, b, c, d, e en f samen de matrix die zal resulteren in de opgegeven rotatie. Wanneer de rotatie rond het middelpunt (0, 0) is, zullen e en f nul zijn.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

De matrix die deze transformatie vertegenwoordigt.

### Zie ook

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
