---
title: Class DocDevice
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Rendering.Doc.DocDevice klas. Vertegenwoordigt weergave naar een DOCXdocument.
type: docs
weight: 4170
url: /nl/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Vertegenwoordigt weergave naar een DOCX-document.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initialiseert een nieuw exemplaar van het`DocDevice` klasse. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initialiseert een nieuw exemplaar van het`DocDevice` klasse per uitvoerstroom. |
| [DocDevice](docdevice/#constructor_5)(string) | Initialiseert een nieuw exemplaar van het`DocDevice` klasse op uitvoerbestandsnaam. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initialiseert een nieuw exemplaar van het`DocDevice` klasse door weergaveopties en streamprovider. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initialiseert een nieuw exemplaar van het`DocDevice` klasse door opties en uitvoerstroom weer te geven. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | Initialiseert een nieuw exemplaar van het`DocDevice` klasse door weergaveopties en uitvoerbestandsnaam. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Voegt een rechthoek toe aan het huidige pad als een volledig subpad. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Begint met het renderen van het document. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Begint de weergave van het html-knooppunt. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Begint met renderen van de nieuwe pagina. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Wijzigt het huidige uitknippad door het te kruisen met het huidige pad, waarbij de FillMode-regel wordt gebruikt om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | Sluit het huidige subpad door een recht lijnstuk toe te voegen vanaf het huidige punt naar het beginpunt van het subpad. Als het huidige subpad al gesloten is, doet "ClosePath" niets. Deze operator beëindigt het huidige subpad. Door nog een segment aan het huidige pad toe te voegen, begint een nieuw subpad, , zelfs als het nieuwe segment begint bij het eindpunt dat wordt bereikt door de "ClosePath"-methode. |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve loopt van het huidige punt naar het punt pt2, met pt1 en pt2 als de Bézier-controlepunten. Het nieuwe huidige punt is pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Tekent de opgegeven afbeelding. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | Beëindigt de weergave van de html-node. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Vult het hele gebied dat wordt ingesloten door het huidige pad. Als het pad uit meerdere niet-verbonden subpaden bestaat, vult het de binnenkant van alle subpaden, samen beschouwd. Deze methode beëindigt het huidige pad. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | Vult de opgegeven tekenreeks op de opgegeven locatie. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | Spoelt alle gegevens naar uitvoerstroom. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Voegt een recht lijnstuk toe vanaf het huidige punt aan het punt (pt). Het nieuwe huidige punt is pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, waarbij elk verbindingslijnsegment wordt weggelaten. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; geen overblijfsel van de vorige "MoveTo"-bewerking blijft in het pad. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze uit de stapel te halen. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Duwt een kopie van de volledige grafische context naar de stapel. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | Trekt een lijn langs het huidige pad. De gestreepte lijn volgt elk recht of gebogen segment in het pad, gecentreerd op het segment met evenwijdige zijden. Elk van de subpaden van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Lijnt en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | Lijnt de gespecificeerde tekstreeks uit op de gespecificeerde locatie. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | Bevat huidige grafische besturingsparameters voor de DocDevice. Deze parameters definiëren het globale raamwerk waarbinnen de grafische operators uitvoeren. |

### Zie ook

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* naamruimte [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* montage [Aspose.HTML](../../)


