---
title: "PdfDevice Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.pdf.PdfDevice Klasse. Stellt das Rendering zu einem PDF-Dokument dar."
type: docs

url: /de/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Stellt das Rendern in ein PDF-Dokument dar.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Initialisiert eine neue Instanz der `PdfDevice` Klasse. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Initialisiert eine neue Instanz der `PdfDevice` Klasse. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | Initialisiert eine neue Instanz der `PdfDevice` Klasse. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Initialisiert eine neue Instanz der `PdfDevice` Klasse mittels Rendering-Optionen und Stream-Anbieter. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Initialisiert eine neue Instanz der `PdfDevice` Klasse mittels Rendering-Optionen und Ausgabestream. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | Initialisiert eine neue Instanz der `PdfDevice` Klasse mittels Rendering-Optionen und Ausgabedateinamen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Methoden

| Name | Beschreibung |
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

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Enthält aktuelle Grafiksteuerungsparameter für das PdfDevice. Diese Parameter definieren das globale Rahmenwerk, innerhalb dessen die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
