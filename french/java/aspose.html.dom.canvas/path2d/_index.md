---
title: "Classe Path2D"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.canvas.Path2D. L'interface Path2D de l'API Canvas 2D est utilisée pour déclarer des chemins qui sont ensuite utilisés sur des objets CanvasRenderingContext2D. Les méthodes de chemin de l'interface CanvasRenderingContext2D sont également présentes sur cette interface et vous permettent de créer des chemins que vous pouvez conserver et rejouer selon les besoins sur un canvas."
type: docs

url: /fr/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

L'interface Path2D de l'API Canvas 2D est utilisée pour déclarer des chemins qui sont ensuite utilisés sur les objets CanvasRenderingContext2D. Les méthodes de chemin de l'interface CanvasRenderingContext2D sont également présentes sur cette interface et vous permettent de créer des chemins que vous pouvez conserver et rejouer selon les besoins sur un canvas.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Path2D](path2d/#constructor)() | renvoie un nouvel objet Path2D |
| [Path2D](path2d/#constructor_1)(Path2D) | renvoie un nouvel objet Path2D avec un autre chemin en argument (crée une copie) |
| [Path2D](path2d/#constructor_2)(String) | renvoie un nouvel objet Path2D avec une chaîne contenant des données de chemin SVG. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Ajoute au chemin le chemin fourni en argument. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Ajoute au chemin le chemin fourni en argument. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Ajoute un arc au chemin centré à la position (x, y) avec un rayon r commençant à startAngle et se terminant à endAngle en suivant la direction donnée, en sens antihoraire (par défaut horaire). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Ajoute un arc au chemin centré à la position (x, y) avec un rayon r commençant à startAngle et se terminant à endAngle en suivant la direction donnée, en sens antihoraire (par défaut horaire). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Ajoute un arc au chemin avec les points de contrôle fournis et le rayon, relié au point précédent par une ligne droite. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Ajoute une courbe de Bézier cubique au chemin. Elle nécessite trois points. Les deux premiers points sont des points de contrôle et le troisième est le point d'arrivée. Le point de départ est le dernier point du chemin actuel, qui peut être modifié avec moveTo() avant de créer la courbe de Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Fait revenir le point du stylo au début du sous‑chemin actuel. Il tente de tracer une ligne droite du point actuel au point de départ. Si la forme a déjà été fermée ou ne comporte qu'un seul point, cette fonction ne fait rien. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Libère l'objet. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Ajoute une ellipse au chemin centrée à la position (x, y) avec les rayons radiusX et radiusY, commençant à startAngle et se terminant à endAngle en suivant la direction donnée, en sens antihoraire (par défaut horaire). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Ajoute une ellipse au chemin centrée à la position (x, y) avec les rayons radiusX et radiusY, commençant à startAngle et se terminant à endAngle en suivant la direction donnée, en sens antihoraire (par défaut horaire). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Relie le dernier point du sous‑chemin aux coordonnées x, y par une ligne droite. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Déplace le point de départ d'un nouveau sous‑chemin vers les coordonnées (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Ajoute une courbe de Bézier quadratique au chemin actuel. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Crée un chemin pour un rectangle à la position (x, y) avec une taille déterminée par la largeur et la hauteur. |

### Voir aussi

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
