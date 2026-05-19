---
title: "Classe PdfDevice"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.rendering.pdf.PdfDevice. Rappresenta il rendering in un documento pdf"
type: docs

url: /it/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Rappresenta il rendering verso un documento PDF.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Inizializza una nuova istanza della classe `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Inizializza una nuova istanza della classe `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | Inizializza una nuova istanza della classe `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Inizializza una nuova istanza della classe `PdfDevice` con opzioni di rendering e provider di stream. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Inizializza una nuova istanza della classe `PdfDevice` con opzioni di rendering e stream di output. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | Inizializza una nuova istanza della classe `PdfDevice` con opzioni di rendering e nome file di output. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Metodi

| Nome | Descrizione |
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

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Contiene i parametri di controllo grafico correnti per il PdfDevice. Questi parametri definiscono il framework globale entro il quale gli operatori grafici vengono eseguiti. |

### Vedi anche

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
