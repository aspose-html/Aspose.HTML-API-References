---
title: Class DocDevice
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Rendering.Doc.DocDevice classe. Représente le rendu dans un document DOCX.
type: docs
weight: 4170
url: /fr/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Représente le rendu dans un document DOCX.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initialise une nouvelle instance du`DocDevice` classe. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initialise une nouvelle instance du`DocDevice` classe par flux de sortie. |
| [DocDevice](docdevice/#constructor_5)(string) | Initialise une nouvelle instance du`DocDevice` classer par nom de fichier de sortie. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initialise une nouvelle instance du`DocDevice` classe en rendant les options et le fournisseur de flux. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initialise une nouvelle instance du`DocDevice` classe en rendant les options et le flux de sortie. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | Initialise une nouvelle instance du`DocDevice` classe en rendant les options et le nom du fichier de sortie. |

## Propriétés

| Nom | La description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Méthodes

| Nom | La description |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Ajoute un rectangle au chemin actuel en tant que sous-chemin complet. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Commence le rendu du document. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Commence le rendu du nœud html. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Commence le rendu de la nouvelle page. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Modifie le chemin de détourage actuel en le croisant avec le chemin actuel, en utilisant la règle FillMode pour déterminer la région à remplir. Cette méthode termine le chemin actuel. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | Ferme le sous-chemin actuel en ajoutant un segment de ligne droite du point actuel au point de départ du sous-chemin. Si le sous-chemin courant est déjà fermé, "ClosePath" ne fait rien. Cet opérateur termine le sous-chemin courant. L'ajout d'un autre segment au chemin actuel commence un nouveau sous-chemin, même si le nouveau segment commence au point final atteint par la méthode "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Ajoute une courbe de Bézier cubique au chemin courant. La courbe s'étend du point courant au point pt2, en utilisant pt1 et pt2 comme points de contrôle de Bézier. Le nouveau point courant est pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Dessine l'image spécifiée. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | Termine le rendu du nœud html. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | Termine le rendu de la page en cours. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Remplit toute la région délimitée par le chemin actuel. Si le chemin se compose de plusieurs sous-chemins déconnectés, il remplit l'intérieur de tous les sous-chemins, considérés ensemble. Cette méthode termine le chemin actuel. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | Remplit la chaîne de texte spécifiée à l'emplacement spécifié. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | Vide toutes les données dans le flux de sortie. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Ajoute un segment de ligne droite du point actuel au point (pt). Le nouveau point courant est pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Commence un nouveau sous-chemin en déplaçant le point courant aux coordonnées du paramètre pt, en omettant tout segment de ligne de connexion. Si la méthode de construction de chemin précédente dans le chemin actuel était également "MoveTo", le nouveau "MoveTo" la remplace ; aucun vestige de l'opération "MoveTo" précédente ne reste dans le chemin. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Restaure l'ensemble du contexte graphique à son ancienne valeur en le détachant de la pile. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Pousse une copie de tout le contexte graphique sur la pile. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | Trace une ligne le long du chemin actuel. La ligne tracée suit chaque segment droit ou courbe du chemin, centré sur le segment avec des côtés parallèles à celui-ci. Chacun des sous-chemins du chemin est traité séparément. Cette méthode termine le chemin actuel. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Traits et remplit le chemin actuel. Cette méthode termine le chemin actuel. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | Trait la chaîne de texte spécifiée à l'emplacement spécifié. |

## Autres membres

| Nom | La description |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | Contient les paramètres de contrôle graphiques actuels pour le DocDevice. Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s'exécutent. |

### Voir également

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* espace de noms [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* Assemblée [Aspose.HTML](../../)


