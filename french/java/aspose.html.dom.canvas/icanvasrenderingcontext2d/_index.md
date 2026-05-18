---
title: "Interface ICanvasRenderingContext2D"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.canvas.ICanvasRenderingContext2D. L'interface ICanvasRenderingContext2D est utilisée pour dessiner des rectangles, du texte, des images et d'autres objets sur l'élément canvas. Elle fournit le contexte de rendu 2D pour la surface de dessin d'un élément canvas."
type: docs

url: /fr/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

L'interface ICanvasRenderingContext2D est utilisée pour dessiner des rectangles, du texte, des images et d'autres objets sur l'élément canvas. Elle fournit le contexte de rendu 2D pour la surface de dessin d'un élément canvas.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) Une référence en lecture seule à l'HTMLCanvasElement. Peut être null si elle n'est pas associée à un élément canvas. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Méthodes

| Nom | Description |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Commence un nouveau chemin en vidant la liste des sous-chemins. Appelez cette méthode lorsque vous souhaitez créer un nouveau chemin. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Supprime toutes les régions de détection du canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Définit tous les pixels du rectangle défini par le point de départ (x, y) et la taille (largeur, hauteur) en noir transparent, effaçant tout contenu précédemment dessiné. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du nombre de tours non nul. Les sous-chemins ouverts doivent être fermés implicitement lors du calcul de la région de découpage, sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du nombre de tours non nul. Les sous-chemins ouverts doivent être fermés implicitement lors du calcul de la région de découpage, sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du nombre de tours non nul. Les sous-chemins ouverts doivent être fermés implicitement lors du calcul de la région de découpage, sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Crée un nouvel objet ImageData vierge avec les dimensions spécifiées. Tous les pixels du nouvel objet sont noirs transparents. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Crée un nouvel objet ImageData vierge avec les dimensions spécifiées. Tous les pixels du nouvel objet sont noirs transparents. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Crée un dégradé linéaire le long de la ligne définie par les coordonnées représentées par les paramètres. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Crée un motif en utilisant l'image spécifiée (un CanvasImageSource). Il répète la source dans les directions spécifiées par l'argument de répétition. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Crée un motif en utilisant l'image spécifiée (un CanvasImageSource). Il répète la source dans les directions spécifiées par l'argument de répétition. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Crée un dégradé radial défini par les coordonnées des deux cercles représentées par les paramètres. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Si un élément donné est focalisé, cette méthode dessine un anneau de focus autour du chemin actuel. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Dessine l'image spécifiée. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Dessine l'image spécifiée. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Dessine l'image spécifiée. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Dessine l'image spécifiée. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Dessine l'image spécifiée. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Dessine l'image spécifiée. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Remplit les sous‑chemins avec le style de remplissage actuel et l'algorithme par défaut CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Remplit les sous‑chemins avec le style de remplissage actuel. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Remplit les sous‑chemins avec le style de remplissage actuel et l'algorithme par défaut CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Remplit les sous‑chemins avec le style de remplissage actuel. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Dessine un rectangle rempli à la position (x, y) dont la taille est déterminée par la largeur et la hauteur. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Dessine (remplit) un texte donné à la position (x,y) donnée. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Dessine (remplit) un texte donné à la position (x,y) donnée. |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Renvoie un objet ImageData représentant les données de pixels sous‑jacentes pour la zone du canevas désignée par le rectangle qui commence à (sx, sy) et possède une largeur sw et une hauteur sh. Cette méthode n'est pas affectée par la matrice de transformation du canevas. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Indique si le point spécifié est ou non contenu dans le chemin actuel. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Indique si le point spécifié est ou non contenu dans le chemin actuel. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Indique si le point spécifié est ou non contenu dans le chemin actuel. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Indique si le point spécifié est ou non contenu dans le chemin actuel. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Indique si le point spécifié est ou non à l'intérieur de la zone contenue par le tracé d'un chemin. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Indique si le point spécifié est ou non à l'intérieur de la zone contenue par le tracé d'un chemin. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Renvoie un objet TextMetrics. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Peint les données de l'objet ImageData donné sur le bitmap. Si un rectangle sale est fourni, seuls les pixels de ce rectangle sont peints. Cette méthode n'est pas affectée par la matrice de transformation du canevas. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Peint les données de l'objet ImageData donné sur le bitmap. Si un rectangle sale est fourni, seuls les pixels de ce rectangle sont peints. Cette méthode n'est pas affectée par la matrice de transformation du canevas. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Supprime la région de clic avec l'ID spécifié du canevas. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Réinitialise la transformation actuelle avec la matrice identité. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Restaure l'état du style de dessin au dernier élément de la « pile d'état » sauvegardée par save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Ajoute une rotation à la matrice de transformation. L'argument angle représente un angle de rotation horaire et est exprimé en radians. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Enregistre l'état actuel du style de dessin à l'aide d'une pile afin que vous puissiez annuler toute modification en l'utilisant avec restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Ajoute une transformation d'échelle aux unités du canevas de x horizontalement et de y verticalement. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Réinitialise la transformation actuelle à la matrice identité, puis invoque la méthode transform() avec les mêmes arguments. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Trace les sous‑chemins avec le style de contour actuel. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Trace les sous‑chemins avec le style de contour actuel. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Peint un rectangle dont le point de départ est à (x, y) et qui a une largeur w et une hauteur h sur le canevas, en utilisant le style de contour actuel. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Dessine (trace) un texte donné à la position (x, y) donnée. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Dessine (trace) un texte donné à la position (x, y) donnée. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multiplie la matrice de transformation actuelle avec la matrice décrite par ses arguments. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Ajoute une transformation de translation en déplaçant le canevas et son origine de x horizontalement et de y verticalement sur la grille. |

### Voir aussi

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
