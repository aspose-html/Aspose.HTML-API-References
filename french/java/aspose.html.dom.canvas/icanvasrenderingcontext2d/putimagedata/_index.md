---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode ICanvasRenderingContext2D. Peint les données de l'objet ImageData fourni sur le bitmap. Si un rectangle sale est fourni, seuls les pixels de ce rectangle sont peints. Cette méthode n'est pas affectée par la matrice de transformation du canvas."
type: docs

url: /fr/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Peint les données de l'objet ImageData donné sur le bitmap. Si un rectangle sale est fourni, seuls les pixels de ce rectangle sont peints. Cette méthode n'est pas affectée par la matrice de transformation du canevas.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imagedata | IImageData | Un objet ImageData contenant le tableau des valeurs de pixels. |
| dx | Double | Position horizontale (coordonnée x) où placer les données d'image dans le canvas de destination. |
| dy | Double | Position verticale (coordonnée y) où placer les données d'image dans le canvas de destination. |

### Voir aussi

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Peint les données de l'objet ImageData donné sur le bitmap. Si un rectangle sale est fourni, seuls les pixels de ce rectangle sont peints. Cette méthode n'est pas affectée par la matrice de transformation du canevas.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imagedata | IImageData | Un objet ImageData contenant le tableau des valeurs de pixels. |
| dx | Double | Position horizontale (coordonnée x) où placer les données d'image dans le canvas de destination. |
| dy | Double | Position verticale (coordonnée y) où placer les données d'image dans le canvas de destination. |
| dirtyX | Double | Position horizontale (coordonnée x). La coordonnée x du coin supérieur gauche de vos Image data. Valeur par défaut 0. |
| dirtyY | Double | Position verticale (coordonnée y). La coordonnée y du coin supérieur gauche de vos Image data. Valeur par défaut 0. |
| dirtyWidth | Double | Largeur du rectangle à peindre. Valeur par défaut la largeur des données d'image. |
| dirtyHeight | Double | Hauteur du rectangle à peindre. Valeur par défaut la hauteur des données d'image. |

### Voir aussi

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
