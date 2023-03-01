---
title: Class XpsDevice
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Rendering.Xps.XpsDevice classe. Représente le rendu dun document xps.
type: docs
weight: 4530
url: /fr/net/aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Représente le rendu d'un document xps.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Initialise une nouvelle instance du`XpsDevice` classe. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Initialise une nouvelle instance du`XpsDevice` classe. |
| [XpsDevice](xpsdevice/#constructor_5)(string) | Initialise une nouvelle instance du`XpsDevice` classe. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initialise une nouvelle instance du`XpsDevice` classe en rendant les options et le fournisseur de flux. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Initialise une nouvelle instance du`XpsDevice`classe en rendant les options et le flux de sortie. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, string) | Initialise une nouvelle instance du`XpsDevice` classe en rendant les options et le nom du fichier de sortie. |

## Propriétés

| Nom | La description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Méthodes

| Nom | La description |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.xps/xpsdevice/addrect/)(RectangleF) | Ajoute un rectangle au chemin actuel en tant que sous-chemin complet. |
| override [BeginDocument](../../aspose.html.rendering.xps/xpsdevice/begindocument/)(Document) | Commence le rendu du document. |
| override [BeginElement](../../aspose.html.rendering.xps/xpsdevice/beginelement/)(Element, RectangleF) | Commence le rendu de l'élément. |
| override [BeginPage](../../aspose.html.rendering.xps/xpsdevice/beginpage/)(SizeF) | Commence le rendu de la nouvelle page. |
| override [Clip](../../aspose.html.rendering.xps/xpsdevice/clip/)(FillMode) | Modifie le chemin de détourage actuel en le croisant avec le chemin actuel, en utilisant la règle FillMode pour déterminer la région à remplir. Cette méthode termine le chemin actuel. |
| override [ClosePath](../../aspose.html.rendering.xps/xpsdevice/closepath/)() | Ferme le sous-chemin actuel en ajoutant un segment de ligne droite du point actuel au point de départ du sous-chemin. Si le sous-chemin courant est déjà fermé, "ClosePath" ne fait rien. Cet opérateur termine le sous-chemin courant. L'ajout d'un autre segment au chemin actuel commence un nouveau sous-chemin, même si le nouveau segment commence au point final atteint par la méthode "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.xps/xpsdevice/cubicbezierto/)(PointF, PointF, PointF) | Ajoute une courbe de Bézier cubique au chemin courant. La courbe s'étend du point courant au point pt2, en utilisant pt1 et pt2 comme points de contrôle de Bézier. Le nouveau point courant est pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.xps/xpsdevice/drawimage/)(byte[], ImageType, RectangleF) | Dessine l'image spécifiée. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.xps/xpsdevice/endelement/)(Element) | Termine le rendu de l'élément. |
| override [EndPage](../../aspose.html.rendering.xps/xpsdevice/endpage/)() | Termine le rendu de la page en cours. |
| override [Fill](../../aspose.html.rendering.xps/xpsdevice/fill/)(FillMode) | Remplit toute la région délimitée par le chemin actuel. Si le chemin se compose de plusieurs sous-chemins déconnectés, il remplit l'intérieur de tous les sous-chemins, considérés ensemble. Cette méthode termine le chemin actuel. |
| override [FillText](../../aspose.html.rendering.xps/xpsdevice/filltext/)(string, PointF) | Remplit la chaîne de texte spécifiée à l'emplacement spécifié. |
| override [Flush](../../aspose.html.rendering.xps/xpsdevice/flush/)() | Vide toutes les données dans le flux de sortie. |
| override [LineTo](../../aspose.html.rendering.xps/xpsdevice/lineto/)(PointF) | Ajoute un segment de ligne droite du point actuel au point (pt). Le nouveau point courant est pt. |
| override [MoveTo](../../aspose.html.rendering.xps/xpsdevice/moveto/)(PointF) | Commence un nouveau sous-chemin en déplaçant le point courant aux coordonnées du paramètre pt, en omettant tout segment de ligne de connexion. Si la méthode de construction de chemin précédente dans le chemin actuel était également "MoveTo", le nouveau "MoveTo" la remplace ; aucun vestige de l'opération "MoveTo" précédente ne reste dans le chemin. |
| override [RestoreGraphicContext](../../aspose.html.rendering.xps/xpsdevice/restoregraphiccontext/)() | Restaure l'ensemble du contexte graphique à son ancienne valeur en le détachant de la pile. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| override [Stroke](../../aspose.html.rendering.xps/xpsdevice/stroke/)() | Trace une ligne le long du chemin actuel. La ligne tracée suit chaque segment droit ou courbe du chemin, centré sur le segment avec des côtés parallèles à celui-ci. Chacun des sous-chemins du chemin est traité séparément. Cette méthode termine le chemin actuel. |
| override [StrokeAndFill](../../aspose.html.rendering.xps/xpsdevice/strokeandfill/)(FillMode) | Traits et remplit le chemin actuel. Cette méthode termine le chemin actuel. |
| override [StrokeText](../../aspose.html.rendering.xps/xpsdevice/stroketext/)(string, PointF) | Trait la chaîne de texte spécifiée à l'emplacement spécifié. |

## Autres membres

| Nom | La description |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext/) | Contient les paramètres de contrôle graphiques actuels pour le XpsDevice. Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s'exécutent. |

### Voir également

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* espace de noms [Aspose.Html.Rendering.Xps](../../aspose.html.rendering.xps/)
* Assemblée [Aspose.HTML](../../)


