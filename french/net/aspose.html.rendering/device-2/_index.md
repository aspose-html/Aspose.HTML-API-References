---
title: DeviceTGraphicContextTRenderingOptions
second_title: Référence de l'API Aspose.HTML pour .NET
description: Représente la classe de base pour limplémentation de dispositifs de rendu particuliers.
type: docs
weight: 4130
url: /fr/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Représente la classe de base pour l'implémentation de dispositifs de rendu particuliers.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Paramètre | La description |
| --- | --- |
| TGraphicContext | Contexte graphique contenant les paramètres de contrôle graphiques actuels |
| TRenderingOptions | Options de rendu |

## Propriétés

| Nom | La description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } | Obtient le contexte graphique |
| [Options](../../aspose.html.rendering/device`2/options) { get; } | Obtient les options de rendu. |

## Méthodes

| Nom | La description |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device`2/addrect)(RectangleF) | Ajoute un rectangle au chemin actuel en tant que sous-chemin complet. |
| virtual [BeginDocument](../../aspose.html.rendering/device`2/begindocument)(Document) | Commence le rendu du document. |
| abstract [BeginElement](../../aspose.html.rendering/device`2/beginelement)(Element, RectangleF) | Commence le rendu du nœud. |
| virtual [BeginPage](../../aspose.html.rendering/device`2/beginpage)(SizeF) | Commence le rendu de la nouvelle page. |
| abstract [Clip](../../aspose.html.rendering/device`2/clip)(FillMode) | Modifie le chemin de détourage actuel en le croisant avec le chemin actuel, en utilisant la règle FillMode pour déterminer la région à remplir. Cette méthode termine le chemin actuel. |
| abstract [ClosePath](../../aspose.html.rendering/device`2/closepath)() | Ferme le sous-chemin actuel en ajoutant un segment de ligne droite du point actuel au point de départ du sous-chemin. Si le sous-chemin courant est déjà fermé, "ClosePath" ne fait rien. Cet opérateur termine le sous-chemin courant. L'ajout d'un autre segment au chemin actuel commence un nouveau sous-chemin, même si le nouveau segment commence au point final atteint par la méthode "ClosePath". |
| abstract [CubicBezierTo](../../aspose.html.rendering/device`2/cubicbezierto)(PointF, PointF, PointF) | Ajoute une courbe de Bézier cubique au chemin courant. La courbe s'étend du point courant au point pt2, en utilisant pt1 et pt2 comme points de contrôle de Bézier. Le nouveau point courant est pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| abstract [DrawImage](../../aspose.html.rendering/device`2/drawimage)(byte[], ImageType, RectangleF) | Dessine l'image spécifiée. |
| virtual [EndDocument](../../aspose.html.rendering/device`2/enddocument)() | Termine le rendu du document. |
| abstract [EndElement](../../aspose.html.rendering/device`2/endelement)(Element) | Termine le rendu du nœud. |
| virtual [EndPage](../../aspose.html.rendering/device`2/endpage)() | Termine le rendu de la page en cours. |
| abstract [Fill](../../aspose.html.rendering/device`2/fill)(FillMode) | Remplit toute la région délimitée par le chemin actuel. Si le chemin se compose de plusieurs sous-chemins déconnectés, il remplit l'intérieur de tous les sous-chemins, considérés ensemble. Cette méthode termine le chemin actuel. |
| abstract [FillText](../../aspose.html.rendering/device`2/filltext)(string, PointF) | Remplit la chaîne de texte spécifiée à l'emplacement spécifié. |
| virtual [Flush](../../aspose.html.rendering/device`2/flush)() | Vide toutes les données dans le flux de sortie. |
| abstract [LineTo](../../aspose.html.rendering/device`2/lineto)(PointF) | Ajoute un segment de ligne droite du point actuel au point (pt). Le nouveau point courant est pt. |
| abstract [MoveTo](../../aspose.html.rendering/device`2/moveto)(PointF) | Commence un nouveau sous-chemin en déplaçant le point courant aux coordonnées du paramètre pt, en omettant tout segment de ligne de connexion. Si la méthode de construction de chemin précédente dans le chemin actuel était également "MoveTo", le nouveau "MoveTo" la remplace ; aucun vestige de l'opération "MoveTo" précédente ne reste dans le chemin. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device`2/restoregraphiccontext)() | Restaure l'ensemble du contexte graphique à son ancienne valeur en le détachant de la pile. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device`2/savegraphiccontext)() | Pousse une copie de tout le contexte graphique sur la pile. |
| abstract [Stroke](../../aspose.html.rendering/device`2/stroke)() | Trace une ligne le long du chemin actuel. La ligne tracée suit chaque segment droit ou courbe du chemin, centré sur le segment avec des côtés parallèles à celui-ci. Chacun des sous-chemins du chemin est traité séparément. Cette méthode termine le chemin actuel. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device`2/strokeandfill)(FillMode) | Traits et remplit le chemin actuel. Cette méthode termine le chemin actuel. |
| abstract [StrokeText](../../aspose.html.rendering/device`2/stroketext)(string, PointF) | Trait la chaîne de texte spécifiée à l'emplacement spécifié. |

## Autres membres

| Nom | La description |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2) | Représente l'objet de configuration pour les appareils. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2) | Spécifie les types de stratégies pour écrire des pages dans le flux de sortie\flux. |

### Voir également

* interface [IDevice](../idevice)
* class [GraphicContext](../graphiccontext)
* class [RenderingOptions](../renderingoptions)
* espace de noms [Aspose.Html.Rendering](../../aspose.html.rendering)
* Assemblée [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
