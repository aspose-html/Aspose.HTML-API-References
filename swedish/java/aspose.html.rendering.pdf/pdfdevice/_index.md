---
title: "PdfDevice-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.pdf.PdfDevice klass. Representerar rendering till ett pdf-dokument"
type: docs

url: /sv/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Representerar rendering till ett PDF‑dokument.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Initierar en ny instans av klassen `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Initierar en ny instans av klassen `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | Initierar en ny instans av klassen `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Initierar en ny instans av klassen `PdfDevice` med renderingsalternativ och strömtillhandahållare. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Initierar en ny instans av klassen `PdfDevice` med renderingsalternativ och utdataström. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | Initierar en ny instans av klassen `PdfDevice` med renderingsalternativ och utdatafilnamn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Metoder

| Namn | Beskrivning |
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

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Innehåller aktuella grafikstyrningsparametrar för PdfDevice. Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna körs. |

### Se även

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
