---
title: Class Path2D
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Canvas.Path2D classe. Linterface Path2D de lAPI Canvas 2D est utilisée pour déclarer des chemins qui seront ensuite utilisés sur les objets CanvasRenderingContext2D. Les méthodes de chemin de linterface CanvasRenderingContext2D sont également présentes sur cette interface et vous permettent de créer des chemins que vous pouvez conserver et rejouer selon vos besoins sur un canevas.
type: docs
weight: 290
url: /fr/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

L'interface Path2D de l'API Canvas 2D est utilisée pour déclarer des chemins qui seront ensuite utilisés sur les objets CanvasRenderingContext2D. Les méthodes de chemin de l'interface CanvasRenderingContext2D sont également présentes sur cette interface et vous permettent de créer des chemins que vous pouvez conserver et rejouer selon vos besoins sur un canevas.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Path2D](path2d/#constructor)() | renvoie un objet Path2D nouvellement instancié |
| [Path2D](path2d/#constructor_1)(Path2D) | renvoie un objet Path2D nouvellement instancié avec un autre chemin comme argument (crée une copie) |
| [Path2D](path2d/#constructor_2)(string) | renvoie un objet Path2D nouvellement instancié avec une chaîne composée de données de chemin SVG. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Ajoute au chemin le chemin donné par l'argument. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Ajoute au chemin le chemin donné par l'argument. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Ajoute un arc au chemin qui est centré à la position (x, y) avec un rayon r commençant à startAngle et se terminant à endAngle allant dans la direction donnée dans le sens inverse des aiguilles d'une montre (par défaut dans le sens des aiguilles d'une montre). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Ajoute un arc au chemin qui est centré à la position (x, y) avec un rayon r commençant à startAngle et se terminant à endAngle allant dans la direction donnée dans le sens inverse des aiguilles d'une montre (par défaut dans le sens des aiguilles d'une montre). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Ajoute un arc au chemin avec les points de contrôle et le rayon donnés, relié au point précédent par une ligne droite. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Ajoute une courbe de Bézier cubique au chemin. Cela nécessite trois points. Les deux premiers points sont des points de contrôle et le troisième est le point final. Le point de départ est le dernier point du chemin actuel, qui peut être modifié à l'aide de moveTo() avant de créer la courbe de Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | Fait reculer la pointe du stylo au début du sous-chemin courant. Il essaie de tracer une ligne droite du point actuel au début. Si la forme a déjà été fermée ou n'a qu'un seul point, cette fonction ne fait rien. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | Supprime l'objet. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Ajoute une ellipse au chemin qui est centrée à la position (x, y) avec les rayons radiusX et radiusY commençant à startAngle et se terminant à endAngle allant dans la direction donnée dans le sens inverse des aiguilles d'une montre (par défaut dans le sens des aiguilles d'une montre). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Ajoute une ellipse au chemin qui est centrée à la position (x, y) avec les rayons radiusX et radiusY commençant à startAngle et se terminant à endAngle allant dans la direction donnée dans le sens inverse des aiguilles d'une montre (par défaut dans le sens des aiguilles d'une montre). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | Relie le dernier point du sous-chemin aux coordonnées x, y par une ligne droite. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | Déplace le point de départ d'un nouveau sous-chemin vers les coordonnées (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Ajoute une courbe de Bézier quadratique au chemin actuel. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Crée un chemin pour un rectangle à la position (x, y) avec une taille déterminée par la largeur et la hauteur. |

### Voir également

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* espace de noms [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* Assemblée [Aspose.HTML](../../)


