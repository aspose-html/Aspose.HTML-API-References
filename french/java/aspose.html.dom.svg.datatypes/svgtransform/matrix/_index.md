---
title: "SVGTransform.Matrix"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété SVGTransform. La matrice qui représente cette transformation. L'objet matrice est dynamique, ce qui signifie que toute modification apportée à l'objet SVGTransform est immédiatement reflétée dans l'objet matrice et vice‑versa. Si l'objet matrice est modifié directement, c’est‑à‑dire sans utiliser les méthodes de l'interface SVGTransform elle‑même, le type de SVGTransform passe à SVG_TRANSFORM_MATRIX. Pour SVG_TRANSFORM_MATRIX, la matrice contient les valeurs a b c d e f fournies par l'utilisateur. Pour SVG_TRANSFORM_TRANSLATE, e et f représentent les quantités de translation (a = 1, b = 0, c = 0 et d = 1). Pour SVG_TRANSFORM_SCALE, a et d représentent les quantités d'échelle (b = 0, c = 0, e = 0 et f = 0). Pour SVG_TRANSFORM_SKEWX et SVG_TRANSFORM_SKEWY, a b c et d représentent la matrice qui produira le biais donné (e = 0 et f = 0). Pour SVG_TRANSFORM_ROTATE, a b c d e et f ensemble représentent la matrice qui produira la rotation donnée. Lorsque la rotation est autour du point central (0, 0), e et f seront zéro."
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

La matrice qui représente cette transformation. L'objet matrice est dynamique, ce qui signifie que toute modification apportée à l'objet SVGTransform est immédiatement reflétée dans l'objet matrice et vice‑versa. Si l'objet matrice est modifié directement (c’est‑à‑dire sans utiliser les méthodes de l'interface SVGTransform elle‑même), le type de SVGTransform passe à SVG_TRANSFORM_MATRIX. Pour SVG_TRANSFORM_MATRIX, la matrice contient les valeurs a, b, c, d, e, f fournies par l'utilisateur. Pour SVG_TRANSFORM_TRANSLATE, e et f représentent les quantités de translation (a = 1, b = 0, c = 0 et d = 1). Pour SVG_TRANSFORM_SCALE, a et d représentent les quantités d'échelle (b = 0, c = 0, e = 0 et f = 0). Pour SVG_TRANSFORM_SKEWX et SVG_TRANSFORM_SKEWY, a, b, c et d représentent la matrice qui produira le biais donné (e = 0 et f = 0). Pour SVG_TRANSFORM_ROTATE, a, b, c, d, e et f ensemble représentent la matrice qui produira la rotation donnée.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

La matrice qui représente cette transformation.

### Voir aussi

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
