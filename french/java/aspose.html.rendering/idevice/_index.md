---
title: "Interface IDevice"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Interface com.aspose.html.rendering.IDevice. Définit les méthodes et propriétés qui prennent en charge le rendu personnalisé des éléments graphiques tels que les chemins, le texte et les images."
type: docs

url: /fr/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Définit les méthodes et propriétés qui prennent en charge le rendu personnalisé des éléments graphiques tels que les chemins, le texte et les images.

```java
public interface IDevice : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Obtient le contexte graphique. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Obtient les options de rendu. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Ajoute un rectangle au chemin actuel en tant que sous‑chemin complet. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Commence le rendu du document. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Commence le rendu de l'élément. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Commence le rendu de la nouvelle page. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Modifie le chemin de découpage actuel en l'intersectant avec le chemin actuel, en utilisant la règle de remplissage (FillRule) pour déterminer la région à remplir. Cette méthode termine le chemin actuel. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Ferme le sous‑chemin actuel en ajoutant un segment de ligne droite du point actuel au point de départ du sous‑chemin. Si le sous‑chemin actuel est déjà fermé, "ClosePath" ne fait rien. Cet opérateur termine le sous‑chemin actuel. Ajouter un autre segment au chemin actuel débute un nouveau sous‑chemin, même si le nouveau segment commence au point final atteint par la méthode "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Ajoute une courbe de Bézier cubique au chemin actuel. La courbe s'étend du point actuel au point pt3, en utilisant pt1 et pt2 comme points de contrôle de Bézier. Le nouveau point actuel est pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Dessine l'image spécifiée. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Termine le rendu du document. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Termine le rendu de l'élément. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Termine le rendu de la page actuelle. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Remplit toute la région délimitée par le chemin actuel. Si le chemin se compose de plusieurs sous‑chemins déconnectés, il remplit l’intérieur de tous les sous‑chemins, considérés ensemble. Cette méthode termine le chemin actuel. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Remplit la String de texte spécifiée à l’emplacement indiqué. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Vide toutes les données vers le flux de sortie. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Ajoute un segment de ligne droite du point actuel au point (pt). Le nouveau point actuel est pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Commence un nouveau sous‑chemin en déplaçant le point actuel aux coordonnées du paramètre pt, en omettant tout segment de ligne de connexion. Si la méthode de construction de chemin précédente dans le chemin actuel était également \"MoveTo\", le nouveau \"MoveTo\" la remplace ; aucun vestige de l’opération \"MoveTo\" précédente ne subsiste dans le chemin. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Restaure l'intégralité du contexte graphique à sa valeur précédente en le dépilant de la pile. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Empile une copie de l'intégralité du contexte graphique. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Trace une ligne le long du chemin actuel. La ligne tracée suit chaque segment droit ou courbe du chemin, centrée sur le segment avec des côtés parallèles. Chacun des sous‑chemins du chemin est traité séparément. Cette méthode termine le chemin actuel. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Trace et remplit le chemin actuel. Cette méthode termine le chemin actuel. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Trace la String de texte spécifiée à l’emplacement indiqué. |

### Voir aussi

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
