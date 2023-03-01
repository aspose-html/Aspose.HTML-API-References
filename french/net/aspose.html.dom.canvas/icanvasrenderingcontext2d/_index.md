---
title: Interface ICanvasRenderingContext2D
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D interface. Linterface ICanvasRenderingContext2D est utilisée pour dessiner des rectangles du texte des images et dautres objets sur lélément canvas. Il fournit le contexte de rendu 2D pour la surface de dessin dun élément canvas.
type: docs
weight: 260
url: /fr/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

L'interface ICanvasRenderingContext2D est utilisée pour dessiner des rectangles, du texte, des images et d'autres objets sur l'élément canvas. Il fournit le contexte de rendu 2D pour la surface de dessin d'un élément canvas.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | Une référence arrière en lecture seule à HTMLCanvasElement. Peut être null s'il n'est pas associé à un élément canvas. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Couleur ou style à utiliser à l'intérieur des formes. Par défaut : (noir). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Valeur alpha appliquée aux formes et aux images avant qu'elles ne soient composées sur le canevas. Par défaut 1.0 (opaque). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | Avec globalAlpha appliqué, cela définit la manière dont les formes et les images sont dessinées sur le bitmap existant. Par défaut : (sur la source) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Mode de lissage d'image ; si désactivé, les images ne seront pas lissées si elles sont mises à l'échelle. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Spécifie l'effet de flou. Par défaut 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Couleur de l'ombre. Noir entièrement transparent par défaut. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Distance horizontale à laquelle l'ombre sera décalée. Par défaut 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Distance verticale à laquelle l'ombre sera décalée. Par défaut 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Couleur ou style à utiliser pour les lignes autour des formes. Par défaut : (noir). |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Ajoute une région d'accès au canevas. Cela vous permet de faciliter la détection des hits, vous permet d'acheminer des événements vers des éléments DOM, et permet aux utilisateurs d'explorer le canevas sans le voir. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Commence un nouveau chemin en vidant la liste des sous-chemins. Appelez cette méthode lorsque vous souhaitez créer un nouveau chemin. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Supprime toutes les régions touchées du canevas. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Définit tous les pixels du rectangle défini par le point de départ (x, y) et la taille (largeur, hauteur) en noir transparent, effaçant tout contenu précédemment dessiné. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du nombre d'enroulement non nul. Les sous-chemins ouverts doivent être implicitement fermés lors du calcul de la région de découpage, sans affecter les sous-chemins réels . La nouvelle région de découpage remplace la région de découpage actuelle. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du numéro d'enroulement non nul. Les sous-chemins ouverts doivent être implicitement fermés lors du calcul de la région de découpage, sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du numéro d'enroulement non nul. Les sous-chemins ouverts doivent être implicitement fermés lors du calcul de la région de découpage, sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Crée un nouvel objet ImageData vide avec les dimensions spécifiées. Tous les pixels du nouvel objet sont en noir transparent. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Crée un nouvel objet ImageData vide avec les dimensions spécifiées. Tous les pixels du nouvel objet sont en noir transparent. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Crée un dégradé linéaire le long de la ligne donnée par les coordonnées représentées par les paramètres. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Crée un motif à l'aide de l'image spécifiée (un CanvasImageSource). Il répète la source dans les directions spécifiées par l'argument de répétition. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Crée un motif à l'aide de l'image spécifiée (un CanvasImageSource). Il répète la source dans les directions spécifiées par l'argument de répétition. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Crée un gradient radial donné par les coordonnées des deux cercles représentés par les paramètres. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Si un élément donné est focalisé, cette méthode dessine un anneau de focus autour du chemin actuel. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Dessine l'image spécifiée. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Dessine l'image spécifiée. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Dessine l'image spécifiée. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Dessine l'image spécifiée. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Dessine l'image spécifiée. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Dessine l'image spécifiée. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Remplit les sous-chemins avec le style de remplissage actuel et l'algorithme par défaut CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Remplit les sous-chemins avec le style de remplissage actuel. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Remplit les sous-chemins avec le style de remplissage actuel et l'algorithme par défaut CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Remplit les sous-chemins avec le style de remplissage actuel. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Dessine un rectangle rempli à la position (x, y) dont la taille est déterminée par la largeur et la hauteur. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Dessine (remplit) un texte donné à la position (x,y) donnée. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Dessine (remplit) un texte donné à la position (x,y) donnée. |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Renvoie un objet ImageData représentant les données de pixel sous-jacentes pour la zone du canevas désignée par le rectangle qui commence à (sx, sy) et a une largeur sw et une hauteur sh. Cette méthode n'est pas affectée par la matrice de transformation du canevas. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Indique si le point spécifié est contenu ou non dans le chemin actuel. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Indique si le point spécifié est contenu ou non dans le chemin actuel. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Indique si le point spécifié est contenu ou non dans le chemin actuel. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Indique si le point spécifié est contenu ou non dans le chemin actuel. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Indique si le point spécifié se trouve ou non à l'intérieur de la zone contenue par le tracé d'un chemin. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Indique si le point spécifié se trouve ou non à l'intérieur de la zone contenue par le tracé d'un chemin. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Renvoie un objet TextMetrics. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Peint les données de l'objet ImageData donné sur le bitmap. Si un rectangle sale est fourni, seuls les pixels de ce rectangle sont peints. Cette méthode n'est pas affectée par la matrice de transformation du canevas. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Peint les données de l'objet ImageData donné sur le bitmap. Si un rectangle sale est fourni, seuls les pixels de ce rectangle sont peints. Cette méthode n'est pas affectée par la matrice de transformation du canevas. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Supprime la région touchée avec l'identifiant spécifié du canevas. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Réinitialise la transformation actuelle par la matrice d'identité. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Restaure l'état du style de dessin au dernier élément de la "pile d'état" enregistrée par save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Ajoute une rotation à la matrice de transformation. L'argument angle représente un angle de rotation dans le sens des aiguilles d'une montre et est exprimé en radians. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Enregistre l'état actuel du style de dessin à l'aide d'une pile afin que vous puissiez annuler toute modification que vous y apportez à l'aide de restore(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Ajoute une transformation de mise à l'échelle aux unités de canevas par x horizontalement et par y verticalement. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Réinitialise la transformation actuelle à la matrice d'identité, puis appelle la méthode transform() avec les mêmes arguments. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Trait les sous-chemins avec le style de trait actuel. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Trait les sous-chemins avec le style de trait actuel. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Peint un rectangle qui a un point de départ à (x, y) et a une largeur aw et une hauteur h sur le canevas, en utilisant le style de trait actuel. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Dessine (traite) un texte donné à la position (x, y) donnée. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Dessine (traite) un texte donné à la position (x, y) donnée. |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multiplie la matrice de transformation courante par la matrice décrite par ses arguments. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Ajoute une transformation de translation en déplaçant le canevas et son origine x horizontalement et y verticalement sur la grille. |

### Voir également

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* espace de noms [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* Assemblée [Aspose.HTML](../../)


