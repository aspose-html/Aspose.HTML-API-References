---
title: "PdfDevice Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.pdf.PdfDevice κλάση. Αναπαριστά την απόδοση σε ένα έγγραφο pdf"
type: docs

url: /el/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Αντιπροσωπεύει την απόδοση σε ένα pdf έγγραφο.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PdfDevice` με επιλογές απόδοσης και πάροχο ροής. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PdfDevice` με επιλογές απόδοσης και ροή εξόδου. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PdfDevice` με επιλογές απόδοσης και όνομα αρχείου εξόδου. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Μέθοδοι

| Όνομα | Περιγραφή |
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

## Άλλα μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Διατηρεί τρέχουσες παραμέτρους ελέγχου γραφικών για το PdfDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών. |

### Δείτε επίσης

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
