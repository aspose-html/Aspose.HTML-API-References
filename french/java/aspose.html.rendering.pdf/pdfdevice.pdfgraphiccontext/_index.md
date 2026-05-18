---
title: "Classe PdfDevice.PdfGraphicContext"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.rendering.pdf.PdfDevicePdfGraphicContext. Contient les paramètres de contrôle graphique actuels pour le PdfDevice. Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s’exécutent."
type: docs

url: /fr/java/com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Contient les paramètres de contrôle graphique actuels pour le PdfDevice. Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s’exécutent.

```java
public class PdfGraphicContext : GraphicContext
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [pdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/.ctor)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Définit ou obtient l'espacement des caractères. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Définit ou obtient l'objet pinceau utilisé pour remplir l'intérieur des chemins. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Définit ou obtient l'objet de police TrueType utilisé pour le rendu du texte. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Définit ou obtient la taille de la police du texte. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Définit ou obtient le style de la police du texte. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Définit ou obtient le code spécifiant la forme des extrémités de tout chemin ouvert qui est tracé. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Définit ou obtient le décalage de phase du motif de tirets de ligne actuel. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Définit ou obtient la description du motif de tirets à utiliser lorsque les chemins sont tracés. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Définit ou obtient le code spécifiant la forme des jointures entre les segments connectés d'un chemin tracé. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Définit ou obtient l'épaisseur des chemins à tracer. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Définit ou obtient la longueur maximale des jointures en onglet pour les chemins tracés. Ce paramètre limite la longueur des \"spikes\" produites lorsque des segments de ligne se rejoignent à des angles aigus. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Définit ou obtient l'objet pinceau utilisé pour les chemins tracés. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Obtient un objet [`TextInfo`](../../com.aspose.html.rendering/textinfo/) qui contient des informations sur le texte rendu. |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | Définit ou obtient la matrice de transformation. |

## Méthodes

| Nom | Description |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Crée une nouvelle instance de la classe GraphicContext avec les mêmes valeurs de propriétés qu'une instance existante. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | Modifie la matrice de transformation actuelle en multipliant par la matrice spécifiée. |

### Voir aussi

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
