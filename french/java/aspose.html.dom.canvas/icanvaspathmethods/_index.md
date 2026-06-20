---
title: "Interface ICanvasPathMethods"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods interface. L'interface ICanvasPathMethods est utilisée pour manipuler les chemins des objets."
type: docs

url: /fr/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

L'interface ICanvasPathMethods est utilisée pour manipuler les chemins des objets.

```java
public interface ICanvasPathMethods
```

## Méthodes

| Nom | Description |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Ajoute un arc au chemin centré à la position (x, y) avec un rayon r commençant à startAngle et se terminant à endAngle en suivant la direction donnée, en sens antihoraire (par défaut horaire). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Ajoute un arc au chemin centré à la position (x, y) avec un rayon r commençant à startAngle et se terminant à endAngle en suivant la direction donnée, en sens antihoraire (par défaut horaire). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Ajoute un arc au chemin avec les points de contrôle fournis et le rayon, relié au point précédent par une ligne droite. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Ajoute une courbe de Bézier cubique au chemin. Elle nécessite trois points. Les deux premiers points sont des points de contrôle et le troisième est le point d'arrivée. Le point de départ est le dernier point du chemin actuel, qui peut être modifié avec moveTo() avant de créer la courbe de Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Fait revenir le point du stylo au début du sous‑chemin actuel. Il tente de tracer une ligne droite du point actuel au point de départ. Si la forme a déjà été fermée ou ne comporte qu'un seul point, cette fonction ne fait rien. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Ajoute une ellipse au chemin centrée à la position (x, y) avec les rayons radiusX et radiusY, commençant à startAngle et se terminant à endAngle en suivant la direction donnée, en sens antihoraire (par défaut horaire). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Ajoute une ellipse au chemin centrée à la position (x, y) avec les rayons radiusX et radiusY, commençant à startAngle et se terminant à endAngle en suivant la direction donnée, en sens antihoraire (par défaut horaire). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Relie le dernier point du sous‑chemin aux coordonnées x, y par une ligne droite. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Déplace le point de départ d'un nouveau sous‑chemin vers les coordonnées (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Ajoute une courbe de Bézier quadratique au chemin actuel. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Crée un chemin pour un rectangle à la position (x, y) avec une taille déterminée par la largeur et la hauteur. |

### Voir aussi

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
