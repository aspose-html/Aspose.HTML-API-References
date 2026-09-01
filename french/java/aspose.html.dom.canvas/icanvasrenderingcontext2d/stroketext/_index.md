---
title: "ICanvasRenderingContext2D.StrokeText"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode ICanvasRenderingContext2D. Trace les contours d'un texte donné à la position x y indiquée"
type: docs

url: /fr/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/
---
## StrokeText(String, double, double) {#stroketext}

Dessine (trace) un texte donné à la position (x, y) donnée.

```java
public void StrokeText(String text, double x, double y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| texte | String | Le texte à dessiner en utilisant les valeurs actuelles de la police, textAlign, textBaseline et direction. |
| x | Double | L'axe x de la coordonnée du point de départ du texte. |
| y | Double | L'axe y de la coordonnée du point de départ du texte. |

### Voir aussi

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## StrokeText(String, double, double, double?) {#stroketext_1}

Dessine (trace) un texte donné à la position (x, y) donnée.

```java
public void StrokeText(String text, double x, double y, double? maxWidth)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| texte | String | Le texte à dessiner en utilisant les valeurs actuelles de la police, textAlign, textBaseline et direction. |
| x | Double | L'axe x de la coordonnée du point de départ du texte. |
| y | Double | L'axe y de la coordonnée du point de départ du texte. |
| maxWidth | Nullable`1 | La largeur maximale à dessiner. Si elle est spécifiée et que la String est calculée comme étant plus large que cette largeur, la police est ajustée pour utiliser une police plus condensée horizontalement (si une telle police est disponible ou si une police raisonnablement lisible peut être synthétisée en redimensionnant horizontalement la police actuelle) ou une police plus petite. |

### Voir aussi

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
