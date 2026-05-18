---
title: "Classe DeviceTGraphicContextTRenderingOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions. Représente la classe de base pour l'implémentation de dispositifs de rendu particuliers."
type: docs

url: /fr/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Représente la classe de base pour l'implémentation d'appareils de rendu particuliers.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Paramètre | Description |
| --- | --- |
| TGraphicContext | Contexte graphique qui contient les paramètres de contrôle graphiques actuels |
| TRenderingOptions | Options de rendu |

## Propriétés

| Nom | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Obtient le contexte graphique |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Obtient les options de rendu. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Ajoute un rectangle au chemin actuel en tant que sous‑chemin complet. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Commence le rendu du document. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Commence le rendu du nœud. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Commence le rendu de la nouvelle page. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Modifie le chemin de découpage actuel en l'intersectant avec le chemin actuel, en utilisant la règle de remplissage (FillRule) pour déterminer la région à remplir. Cette méthode termine le chemin actuel. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Ferme le sous‑chemin actuel en ajoutant un segment de ligne droite du point actuel au point de départ du sous‑chemin. Si le sous‑chemin actuel est déjà fermé, "ClosePath" ne fait rien. Cet opérateur termine le sous‑chemin actuel. Ajouter un autre segment au chemin actuel débute un nouveau sous‑chemin, même si le nouveau segment commence au point final atteint par la méthode "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Ajoute une courbe cubique de Bézier au chemin actuel. La courbe s'étend du point actuel au point pt2, en utilisant pt1 et pt2 comme points de contrôle du Bézier. Le nouveau point actuel est pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Dessine l'image spécifiée. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Termine le rendu du document. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Termine le rendu du nœud. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Termine le rendu de la page actuelle. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Remplit toute la région délimitée par le chemin actuel. Si le chemin se compose de plusieurs sous‑chemins déconnectés, il remplit l’intérieur de tous les sous‑chemins, considérés ensemble. Cette méthode termine le chemin actuel. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Remplit la String de texte spécifiée à l’emplacement indiqué. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Vide toutes les données vers le flux de sortie. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Ajoute un segment de ligne droite du point actuel au point (pt). Le nouveau point actuel est pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Commence un nouveau sous‑chemin en déplaçant le point actuel aux coordonnées du paramètre pt, en omettant tout segment de ligne de connexion. Si la méthode de construction de chemin précédente dans le chemin actuel était également \"MoveTo\", le nouveau \"MoveTo\" la remplace ; aucun vestige de l’opération \"MoveTo\" précédente ne subsiste dans le chemin. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Restaure l'intégralité du contexte graphique à sa valeur précédente en le dépilant de la pile. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Empile une copie de l'intégralité du contexte graphique. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Trace une ligne le long du chemin actuel. La ligne tracée suit chaque segment droit ou courbe du chemin, centrée sur le segment avec des côtés parallèles. Chacun des sous‑chemins du chemin est traité séparément. Cette méthode termine le chemin actuel. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Trace et remplit le chemin actuel. Cette méthode termine le chemin actuel. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Trace la String de texte spécifiée à l’emplacement indiqué. |

## Autres membres

| Nom | Description |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Spécifie les types de stratégies pour écrire les pages dans des flux de sortie\\flux. |

### Voir aussi

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
