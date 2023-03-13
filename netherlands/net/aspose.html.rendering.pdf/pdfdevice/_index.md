---
title: Class PdfDevice
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Rendering.Pdf.PdfDevice klas. Vertegenwoordigt weergave naar een pdfdocument.
type: docs
weight: 4440
url: /nl/net/aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Vertegenwoordigt weergave naar een pdf-document.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Initialiseert een nieuw exemplaar van het`PdfDevice` klasse. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Initialiseert een nieuw exemplaar van het`PdfDevice` klasse. |
| [PdfDevice](pdfdevice/#constructor_5)(string) | Initialiseert een nieuw exemplaar van het`PdfDevice` klasse. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Initialiseert een nieuw exemplaar van het`PdfDevice` klasse door weergaveopties en streamprovider. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Initialiseert een nieuw exemplaar van het`PdfDevice`klasse door opties en uitvoerstroom weer te geven. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, string) | Initialiseert een nieuw exemplaar van het`PdfDevice` klasse door weergaveopties en uitvoerbestandsnaam. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.pdf/pdfdevice/addrect/)(RectangleF) | Voegt een rechthoek toe aan het huidige pad als een volledig subpad. |
| override [BeginDocument](../../aspose.html.rendering.pdf/pdfdevice/begindocument/)(Document) | Begint met het renderen van het document. |
| override [BeginElement](../../aspose.html.rendering.pdf/pdfdevice/beginelement/)(Element, RectangleF) | Begint met renderen van het element. |
| override [BeginPage](../../aspose.html.rendering.pdf/pdfdevice/beginpage/)(SizeF) | Begint met renderen van de nieuwe pagina. |
| override [Clip](../../aspose.html.rendering.pdf/pdfdevice/clip/)(FillMode) | Wijzigt het huidige uitknippad door het te kruisen met het huidige pad, waarbij de FillMode-regel wordt gebruikt om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| override [ClosePath](../../aspose.html.rendering.pdf/pdfdevice/closepath/)() | Sluit het huidige subpad door een recht lijnstuk toe te voegen vanaf het huidige punt naar het beginpunt van het subpad. Als het huidige subpad al gesloten is, doet "ClosePath" niets. Deze operator beëindigt het huidige subpad. Door nog een segment aan het huidige pad toe te voegen, begint een nieuw subpad, , zelfs als het nieuwe segment begint bij het eindpunt dat wordt bereikt door de "ClosePath"-methode. |
| override [CubicBezierTo](../../aspose.html.rendering.pdf/pdfdevice/cubicbezierto/)(PointF, PointF, PointF) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve loopt van het huidige punt naar het punt pt2, met pt1 en pt2 als de Bézier-controlepunten. Het nieuwe huidige punt is pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.pdf/pdfdevice/drawimage/)(byte[], ImageType, RectangleF) | Tekent de opgegeven afbeelding. |
| override [EndDocument](../../aspose.html.rendering.pdf/pdfdevice/enddocument/)() | Beëindigt de weergave van het document. |
| override [EndElement](../../aspose.html.rendering.pdf/pdfdevice/endelement/)(Element) | Beëindigt het renderen van het element. |
| override [EndPage](../../aspose.html.rendering.pdf/pdfdevice/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| override [Fill](../../aspose.html.rendering.pdf/pdfdevice/fill/)(FillMode) | Vult het hele gebied dat wordt ingesloten door het huidige pad. Als het pad uit meerdere niet-verbonden subpaden bestaat, vult het de binnenkant van alle subpaden, samen beschouwd. Deze methode beëindigt het huidige pad. |
| override [FillText](../../aspose.html.rendering.pdf/pdfdevice/filltext/)(string, PointF) | Vult de opgegeven tekenreeks op de opgegeven locatie. |
| override [Flush](../../aspose.html.rendering.pdf/pdfdevice/flush/)() | Spoelt alle gegevens naar uitvoerstroom. |
| override [LineTo](../../aspose.html.rendering.pdf/pdfdevice/lineto/)(PointF) | Voegt een recht lijnstuk toe vanaf het huidige punt aan het punt (pt). Het nieuwe huidige punt is pt. |
| override [MoveTo](../../aspose.html.rendering.pdf/pdfdevice/moveto/)(PointF) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, waarbij elk verbindingslijnsegment wordt weggelaten. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; geen overblijfsel van de vorige "MoveTo"-bewerking blijft in het pad. |
| override [RestoreGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze uit de stapel te halen. |
| override [SaveGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/savegraphiccontext/)() | Duwt een kopie van de volledige grafische context naar de stapel. |
| override [Stroke](../../aspose.html.rendering.pdf/pdfdevice/stroke/)() | Trekt een lijn langs het huidige pad. De gestreepte lijn volgt elk recht of gebogen segment in het pad, gecentreerd op het segment met evenwijdige zijden. Elk van de subpaden van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| override [StrokeAndFill](../../aspose.html.rendering.pdf/pdfdevice/strokeandfill/)(FillMode) | Lijnt en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| override [StrokeText](../../aspose.html.rendering.pdf/pdfdevice/stroketext/)(string, PointF) | Lijnt de gespecificeerde tekstreeks uit op de gespecificeerde locatie. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [PdfGraphicContext](pdfdevice.pdfgraphiccontext/) | Bevat huidige grafische besturingsparameters voor het PdfDevice. Deze parameters bepalen het globale raamwerk waarbinnen de grafische operators uitvoeren. |

### Zie ook

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* naamruimte [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* montage [Aspose.HTML](../../)


