---
title: "SVGPathSeg Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg classe. L'interface SVGPathSeg est une interface de base qui correspond à une seule commande dans une spécification de données de chemin."
type: docs

url: /fr/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

L'interface SVGPathSeg est une interface de base qui correspond à une commande unique dans une spécification de données de chemin.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) Le type du segment de chemin tel que spécifié par l’une des constantes définies sur cette interface. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Le type du segment de chemin, spécifié par le nom de commande d’un caractère correspondant. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |

## Champs

| Nom | Description |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Correspond à une commande de données de chemin « arcto absolu » (A). |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Correspond à une commande de données de chemin « arcto relatif » (a). |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Correspond à une commande de données de chemin « closepath » (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Correspond à une commande de données de chemin « cubic Bézier curveto absolu » (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Correspond à une commande de données de chemin « cubic Bézier curveto relatif » (c). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Correspond à une commande de données de chemin « smooth cubic curveto absolu » (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Correspond à une commande de données de chemin « smooth cubic curveto relatif » (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Correspond à une commande de données de chemin « quadratic Bézier curveto absolu » (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Correspond à une commande de données de chemin « quadratic Bézier curveto relatif » (q). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Correspond à une commande de données de chemin « smooth quadratic curveto absolu » (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Correspond à une "courbe quadratique lisse relative" (t) commande de données de chemin. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Correspond à une "lineto absolu" (L) commande de données de chemin. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Correspond à une "lineto horizontal absolu" (H) commande de données de chemin. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Correspond à une "lineto horizontal relatif" (h) commande de données de chemin. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Correspond à une "lineto relatif" (l) commande de données de chemin. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Correspond à une "lineto vertical absolu" (V) commande de données de chemin. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Correspond à une "lineto vertical relatif" (v) commande de données de chemin. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Correspond à une "moveto absolu" (M) commande de données de chemin. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Correspond à une "moveto relatif" (m) commande de données de chemin. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Le type d'unité n'est pas l'un des types prédéfinis. Il est invalide de tenter de définir une nouvelle valeur de ce type ou d'essayer de basculer une valeur existante vers ce type. |

### Voir aussi

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
