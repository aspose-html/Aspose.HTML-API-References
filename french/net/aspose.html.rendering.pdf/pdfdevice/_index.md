---
title: PdfDevice
second_title: Référence de l'API Aspose.HTML pour .NET
description: Représente le rendu dun document pdf.
type: docs
weight: 4420
url: /fr/net/aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Représente le rendu d'un document pdf.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfDevice](pdfdevice#constructor)(ICreateStreamProvider) | Initialise une nouvelle instance du[`PdfDevice`](../pdfdevice) classe. |
| [PdfDevice](pdfdevice#constructor_4)(Stream) | Initialise une nouvelle instance du[`PdfDevice`](../pdfdevice) classe. |
| [PdfDevice](pdfdevice#constructor_5)(string) | Initialise une nouvelle instance du[`PdfDevice`](../pdfdevice) classe. |
| [PdfDevice](pdfdevice#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Initialise une nouvelle instance du[`PdfDevice`](../pdfdevice) classe en rendant les options et le fournisseur de flux. |
| [PdfDevice](pdfdevice#constructor_2)(PdfRenderingOptions, Stream) | Initialise une nouvelle instance du[`PdfDevice`](../pdfdevice)classe en rendant les options et le flux de sortie. |
| [PdfDevice](pdfdevice#constructor_3)(PdfRenderingOptions, string) | Initialise une nouvelle instance du[`PdfDevice`](../pdfdevice) classe en rendant les options et le nom du fichier de sortie. |

## Propriétés

| Nom | La description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.html.rendering/device`2/options) { get; } |  |

## Méthodes

| Nom | La description |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.pdf/pdfdevice/addrect)(RectangleF) | Ajoute un rectangle au chemin actuel en tant que sous-chemin complet. |
| override [BeginDocument](../../aspose.html.rendering.pdf/pdfdevice/begindocument)(Document) | Commence le rendu du document. |
| override [BeginElement](../../aspose.html.rendering.pdf/pdfdevice/beginelement)(Element, RectangleF) | Commence le rendu de l'élément. |
| override [BeginPage](../../aspose.html.rendering.pdf/pdfdevice/beginpage)(SizeF) | Commence le rendu de la nouvelle page. |
| override [Clip](../../aspose.html.rendering.pdf/pdfdevice/clip)(FillMode) | Modifie le chemin de détourage actuel en le croisant avec le chemin actuel, en utilisant la règle FillMode pour déterminer la région à remplir. Cette méthode termine le chemin actuel. |
| override [ClosePath](../../aspose.html.rendering.pdf/pdfdevice/closepath)() | Ferme le sous-chemin actuel en ajoutant un segment de ligne droite du point actuel au point de départ du sous-chemin. Si le sous-chemin courant est déjà fermé, "ClosePath" ne fait rien. Cet opérateur termine le sous-chemin courant. L'ajout d'un autre segment au chemin actuel commence un nouveau sous-chemin, même si le nouveau segment commence au point final atteint par la méthode "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.pdf/pdfdevice/cubicbezierto)(PointF, PointF, PointF) | Ajoute une courbe de Bézier cubique au chemin courant. La courbe s'étend du point courant au point pt2, en utilisant pt1 et pt2 comme points de contrôle de Bézier. Le nouveau point courant est pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.html.rendering.pdf/pdfdevice/drawimage)(byte[], ImageType, RectangleF) | Dessine l'image spécifiée. |
| override [EndDocument](../../aspose.html.rendering.pdf/pdfdevice/enddocument)() | Termine le rendu du document. |
| override [EndElement](../../aspose.html.rendering.pdf/pdfdevice/endelement)(Element) | Termine le rendu de l'élément. |
| override [EndPage](../../aspose.html.rendering.pdf/pdfdevice/endpage)() | Termine le rendu de la page en cours. |
| override [Fill](../../aspose.html.rendering.pdf/pdfdevice/fill)(FillMode) | Remplit toute la région délimitée par le chemin actuel. Si le chemin se compose de plusieurs sous-chemins déconnectés, il remplit l'intérieur de tous les sous-chemins, considérés ensemble. Cette méthode termine le chemin actuel. |
| override [FillText](../../aspose.html.rendering.pdf/pdfdevice/filltext)(string, PointF) | Remplit la chaîne de texte spécifiée à l'emplacement spécifié. |
| override [Flush](../../aspose.html.rendering.pdf/pdfdevice/flush)() | Vide toutes les données dans le flux de sortie. |
| override [LineTo](../../aspose.html.rendering.pdf/pdfdevice/lineto)(PointF) | Ajoute un segment de ligne droite du point actuel au point (pt). Le nouveau point courant est pt. |
| override [MoveTo](../../aspose.html.rendering.pdf/pdfdevice/moveto)(PointF) | Commence un nouveau sous-chemin en déplaçant le point courant aux coordonnées du paramètre pt, en omettant tout segment de ligne de connexion. Si la méthode de construction de chemin précédente dans le chemin actuel était également "MoveTo", le nouveau "MoveTo" la remplace ; aucun vestige de l'opération "MoveTo" précédente ne reste dans le chemin. |
| override [RestoreGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/restoregraphiccontext)() | Restaure l'ensemble du contexte graphique à son ancienne valeur en le détachant de la pile. |
| override [SaveGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/savegraphiccontext)() | Pousse une copie de tout le contexte graphique sur la pile. |
| override [Stroke](../../aspose.html.rendering.pdf/pdfdevice/stroke)() | Trace une ligne le long du chemin actuel. La ligne tracée suit chaque segment droit ou courbe du chemin, centré sur le segment avec des côtés parallèles à celui-ci. Chacun des sous-chemins du chemin est traité séparément. Cette méthode termine le chemin actuel. |
| override [StrokeAndFill](../../aspose.html.rendering.pdf/pdfdevice/strokeandfill)(FillMode) | Traits et remplit le chemin actuel. Cette méthode termine le chemin actuel. |
| override [StrokeText](../../aspose.html.rendering.pdf/pdfdevice/stroketext)(string, PointF) | Trait la chaîne de texte spécifiée à l'emplacement spécifié. |

## Autres membres

| Nom | La description |
| --- | --- |
| class [PdfGraphicContext](pdfdevice.pdfgraphiccontext) | Contient les paramètres de contrôle graphiques actuels pour le PdfDevice. Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s'exécutent. |

### Voir également

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext)
* class [PdfRenderingOptions](../pdfrenderingoptions)
* espace de noms [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf)
* Assemblée [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
