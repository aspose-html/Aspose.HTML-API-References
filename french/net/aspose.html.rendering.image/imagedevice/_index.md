---
title: Class ImageDevice
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Rendering.Image.ImageDevice classe. Représente le rendu aux formats raster  jpeg png bmp gif tiff.
type: docs
weight: 4300
url: /fr/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Représente le rendu aux formats raster : jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Initialise une nouvelle instance du`ImageDevice` classe. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Initialise une nouvelle instance du`ImageDevice` classe. |
| [ImageDevice](imagedevice/#constructor_5)(string) | Initialise une nouvelle instance du`ImageDevice` classe. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Initialise une nouvelle instance du`ImageDevice` classe en rendant les options et le fournisseur de flux. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Initialise une nouvelle instance du`ImageDevice`classe en rendant les options et le flux de sortie. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | Initialise une nouvelle instance du`ImageDevice` classe en rendant les options et le nom du fichier de sortie. |

## Propriétés

| Nom | La description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Obtient l'instance de Graphics. |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Méthodes

| Nom | La description |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | Ajoute un rectangle au chemin actuel en tant que sous-chemin complet. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | Commence le rendu du document. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | Commence le rendu de l'élément. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | Commence le rendu de la nouvelle page. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | Modifie le chemin de détourage actuel en le croisant avec le chemin actuel, en utilisant la règle FillMode pour déterminer la région à remplir. Cette méthode termine le chemin actuel. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | Ferme le sous-chemin actuel en ajoutant un segment de ligne droite du point actuel au point de départ du sous-chemin. Si le sous-chemin courant est déjà fermé, "ClosePath" ne fait rien. Cet opérateur termine le sous-chemin courant. L'ajout d'un autre segment au chemin actuel commence un nouveau sous-chemin, même si le nouveau segment commence au point final atteint par la méthode "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | Ajoute une courbe de Bézier cubique au chemin courant. La courbe s'étend du point courant au point pt2, en utilisant pt1 et pt2 comme points de contrôle de Bézier. Le nouveau point courant est pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | Dessine l'image spécifiée. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | Termine le rendu du document. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | Termine le rendu de l'élément. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | Termine le rendu de la page en cours. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | Remplit toute la région délimitée par le chemin actuel. Si le chemin se compose de plusieurs sous-chemins déconnectés, il remplit l'intérieur de tous les sous-chemins, considérés ensemble. Cette méthode termine le chemin actuel. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | Remplit la chaîne de texte spécifiée à l'emplacement spécifié. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | Vide toutes les données dans le flux de sortie. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | Ajoute un segment de ligne droite du point actuel au point (pt). Le nouveau point courant est pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | Commence un nouveau sous-chemin en déplaçant le point courant aux coordonnées du paramètre pt, en omettant tout segment de ligne de connexion. Si la méthode de construction de chemin précédente dans le chemin actuel était également "MoveTo", le nouveau "MoveTo" la remplace ; aucun vestige de l'opération "MoveTo" précédente ne reste dans le chemin. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | Restaure l'ensemble du contexte graphique à son ancienne valeur en le détachant de la pile. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | Pousse une copie de tout le contexte graphique sur la pile. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | Trace une ligne le long du chemin actuel. La ligne tracée suit chaque segment droit ou courbe du chemin, centré sur le segment avec des côtés parallèles à celui-ci. Chacun des sous-chemins du chemin est traité séparément. Cette méthode termine le chemin actuel. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | Traits et remplit le chemin actuel. Cette méthode termine le chemin actuel. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | Trait la chaîne de texte spécifiée à l'emplacement spécifié. |

## Autres membres

| Nom | La description |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | Contient les paramètres de contrôle graphiques actuels pour le`ImageDevice` . Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s'exécutent. |

### Voir également

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* espace de noms [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* Assemblée [Aspose.HTML](../../)


