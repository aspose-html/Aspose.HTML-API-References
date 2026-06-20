---
title: "PdfDevice Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.rendering.pdf.PdfDevice. Représente le rendu vers un document PDF"
type: docs

url: /fr/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Représente le rendu vers un document PDF.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Initialise une nouvelle instance de la classe `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Initialise une nouvelle instance de la classe `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | Initialise une nouvelle instance de la classe `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Initialise une nouvelle instance de la classe `PdfDevice` à l'aide des options de rendu et du fournisseur de flux. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Initialise une nouvelle instance de la classe `PdfDevice` à l'aide des options de rendu et du flux de sortie. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | Initialise une nouvelle instance de la classe `PdfDevice` à l'aide des options de rendu et du nom de fichier de sortie. |

## Propriétés

| Nom | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Méthodes

| Nom | Description |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) |  |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) |  |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() |  |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) |  |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() |  |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) |  |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) |  |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() |  |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) |  |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) |  |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() |  |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) |  |

## Autres membres

| Nom | Description |
| --- | --- |
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Contient les paramètres de contrôle graphique actuels pour le PdfDevice. Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s’exécutent. |

### Voir aussi

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
