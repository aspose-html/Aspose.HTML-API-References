---
title: "ISVGAnimatedPathData Interface"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData interface. L'interface SVGAnimatedPathData prend en charge les éléments qui possèdent un attribut d contenant des données de chemin SVG et permet d'animer cet attribut."
type: docs

url: /fr/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

L'interface SVGAnimatedPathData prend en charge les éléments qui ont un attribut ‘d’ contenant des données de chemin SVG, et permet d’animer cet attribut.

```java
public interface ISVGAnimatedPathData
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Fournit l'accès au contenu animé actuel de l'attribut ‘d’ sous une forme qui correspond exactement à la syntaxe SVG. Si l'attribut ou la propriété donné(e) est animé(e), il contient la valeur animée actuelle de l'attribut ou de la propriété, et l'objet ainsi que son contenu sont en lecture seule. Si l'attribut ou la propriété n'est pas actuellement animé(e), il contient la même valeur que pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Fournit l'accès au contenu de base (c’est‑à‑dire statique) de l'attribut ‘d’ sous une forme qui correspond exactement à la syntaxe SVG. Ainsi, si l'attribut ‘d’ possède une commande « moveto absolu (M) » et une commande « arcto absolu (A) », alors pathSegList contiendra deux entrées : un SVG_PATHSEG_MOVETO_ABS et un SVG_PATHSEG_ARC_ABS. |

### Voir aussi

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
