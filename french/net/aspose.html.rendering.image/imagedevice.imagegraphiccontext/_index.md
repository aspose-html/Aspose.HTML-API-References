---
title: Class ImageDevice.ImageGraphicContext
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Rendering.Image.ImageDeviceImageGraphicContext classe. Contient les paramètres de contrôle graphiques actuels pour leImageDevice . Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques sexécutent.
type: docs
weight: 4310
url: /fr/net/aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Contient les paramètres de contrôle graphiques actuels pour le[`ImageDevice`](../imagedevice/) . Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s'exécutent.

```csharp
public class ImageGraphicContext : GraphicContext
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageGraphicContext](imagegraphiccontext/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Définit ou obtient l'espacement des caractères. |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Définit ou obtient l'objet pinceau utilisé pour remplir l'intérieur des chemins. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Définit ou obtient l'objet de police True Type utilisé pour le rendu du texte. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Définit ou obtient la taille de la police du texte. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Définit ou obtient le style de police du texte. |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Définit ou obtient le code spécifiant la forme des points de terminaison pour tout chemin ouvert tracé. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Définit ou obtient le décalage de phase du motif de tiret de ligne actuel. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Définit ou obtient la description du motif de tirets à utiliser lorsque les chemins sont tracés. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Ensembles de obtient le style des lignes en pointillés d'un chemin tracé. |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Définit ou obtient le code spécifiant la forme des joints entre les segments connectés d'un tracé tracé. |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Définit ou obtient l'épaisseur des chemins à tracer. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Définit ou obtient la longueur maximale des jointures de lignes en onglet pour les chemins tracés. Ce paramètre limite la longueur des "pointes" produites lorsque les segments de ligne se rejoignent à des angles vifs. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Définit ou obtient l'objet pinceau utilisé pour les tracés tracés. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Obtient un[`TextInfo`](../../aspose.html.rendering/textinfo/) objet qui contient des informations sur le texte rendu. |
| override [TransformationMatrix](../../aspose.html.rendering.image/imagegraphiccontext/transformationmatrix/) { get; set; } | Définit ou obtient la matrice de transformation. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../aspose.html.rendering.image/imagegraphiccontext/clone/)() | Crée une nouvelle instance d'une classe GdiGraphicContext avec les mêmes valeurs de propriété qu'une instance existante. |
| override [Transform](../../aspose.html.rendering.image/imagegraphiccontext/transform/)(Matrix) | Modifier la matrice de transformation actuelle en multipliant la matrice spécifiée. |

### Voir également

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* espace de noms [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* Assemblée [Aspose.HTML](../../)


