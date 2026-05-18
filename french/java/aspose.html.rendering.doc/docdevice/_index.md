---
title: "DocDevice Class"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.rendering.doc.DocDevice class. Représente le rendu vers un document DOCX"
type: docs

url: /fr/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Représente le rendu vers un document DOCX.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initialise une nouvelle instance de la classe `DocDevice`. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initialise une nouvelle instance de la classe `DocDevice` par flux de sortie. |
| [DocDevice](docdevice/#constructor_5)(String) | Initialise une nouvelle instance de la classe `DocDevice` par nom de fichier de sortie. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initialise une nouvelle instance de la classe `DocDevice` avec des options de rendu et un fournisseur de flux. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initialise une nouvelle instance de la classe `DocDevice` avec des options de rendu et un flux de sortie. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Initialise une nouvelle instance de la classe `DocDevice` avec des options de rendu et un nom de fichier de sortie. |

## Propriétés

| Nom | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Méthodes

| Nom | Description |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Ajoute un rectangle au chemin actuel en tant que sous‑chemin complet. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Commence le rendu du document. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Commence le rendu du nœud html. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Commence le rendu de la nouvelle page. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Modifie le chemin de découpage actuel en l’intersectant avec le chemin actuel, en utilisant la règle FillMode pour déterminer la région à remplir. Cette méthode termine le chemin actuel. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Ferme le sous‑chemin actuel en ajoutant un segment de ligne droite du point actuel au point de départ du sous‑chemin. Si le sous‑chemin actuel est déjà fermé, "ClosePath" ne fait rien. Cet opérateur termine le sous‑chemin actuel. Ajouter un autre segment au chemin actuel débute un nouveau sous‑chemin, même si le nouveau segment commence au point final atteint par la méthode "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Ajoute une courbe cubique de Bézier au chemin actuel. La courbe s'étend du point actuel au point pt2, en utilisant pt1 et pt2 comme points de contrôle du Bézier. Le nouveau point actuel est pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Dessine l'image spécifiée. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Termine le rendu du nœud html. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Termine le rendu de la page actuelle. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Remplit toute la région délimitée par le chemin actuel. Si le chemin se compose de plusieurs sous‑chemins déconnectés, il remplit l’intérieur de tous les sous‑chemins, considérés ensemble. Cette méthode termine le chemin actuel. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Remplit la String de texte spécifiée à l’emplacement indiqué. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Vide toutes les données vers le flux de sortie. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Ajoute un segment de ligne droite du point actuel au point (pt). Le nouveau point actuel est pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Commence un nouveau sous‑chemin en déplaçant le point actuel aux coordonnées du paramètre pt, en omettant tout segment de ligne de connexion. Si la méthode de construction de chemin précédente dans le chemin actuel était également \"MoveTo\", le nouveau \"MoveTo\" la remplace ; aucun vestige de l’opération \"MoveTo\" précédente ne subsiste dans le chemin. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Trace une ligne le long du chemin actuel. La ligne tracée suit chaque segment droit ou courbe du chemin, centrée sur le segment avec des côtés parallèles. Chacun des sous‑chemins du chemin est traité séparément. Cette méthode termine le chemin actuel. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Trace et remplit le chemin actuel. Cette méthode termine le chemin actuel. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Trace la String de texte spécifiée à l’emplacement indiqué. |

## Autres membres

| Nom | Description |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Contient les paramètres de contrôle graphique actuels pour le DocDevice. Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s’exécutent. |

### Voir aussi

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
