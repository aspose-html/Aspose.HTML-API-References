---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions klas. Vertegenwoordigt basisklasse voor implementatie van bepaalde weergaveapparaten.
type: docs
weight: 4140
url: /nl/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Vertegenwoordigt basisklasse voor implementatie van bepaalde weergaveapparaten.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Beschrijving |
| --- | --- |
| TGraphicContext | Grafische context die de huidige grafische besturingsparameters bevat |
| TRenderingOptions | Weergave opties |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | Krijgt de grafische context |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | Krijgt weergave-opties. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | Voegt een rechthoek toe aan het huidige pad als een volledig subpad. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | Begint met het renderen van het document. |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Begint de weergave van het knooppunt. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | Begint met renderen van de nieuwe pagina. |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | Wijzigt het huidige uitknippad door het te kruisen met het huidige pad, waarbij de FillMode-regel wordt gebruikt om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | Sluit het huidige subpad door een recht lijnstuk toe te voegen vanaf het huidige punt naar het beginpunt van het subpad. Als het huidige subpad al gesloten is, doet "ClosePath" niets. Deze operator beëindigt het huidige subpad. Door nog een segment aan het huidige pad toe te voegen, begint een nieuw subpad, , zelfs als het nieuwe segment begint bij het eindpunt dat wordt bereikt door de "ClosePath"-methode. |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve loopt van het huidige punt naar het punt pt2, met pt1 en pt2 als de Bézier-controlepunten. Het nieuwe huidige punt is pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijmaken, vrijgeven of resetten van onbeheerde bronnen. |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | Tekent de opgegeven afbeelding. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | Beëindigt de weergave van het document. |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | Beëindigt de weergave van het knooppunt. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | Vult het hele gebied dat wordt ingesloten door het huidige pad. Als het pad uit meerdere niet-verbonden subpaden bestaat, vult het de binnenkant van alle subpaden, samen beschouwd. Deze methode beëindigt het huidige pad. |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | Vult de opgegeven tekenreeks op de opgegeven locatie. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | Spoelt alle gegevens naar uitvoerstroom. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | Voegt een recht lijnstuk toe vanaf het huidige punt aan het punt (pt). Het nieuwe huidige punt is pt. |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, waarbij elk verbindingslijnsegment wordt weggelaten. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; geen overblijfsel van de vorige "MoveTo"-bewerking blijft in het pad. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze uit de stapel te halen. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | Duwt een kopie van de volledige grafische context naar de stapel. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | Trekt een lijn langs het huidige pad. De gestreepte lijn volgt elk recht of gebogen segment in het pad, gecentreerd op het segment met evenwijdige zijden. Elk van de subpaden van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | Lijnt en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | Lijnt de gespecificeerde tekstreeks uit op de gespecificeerde locatie. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | Vertegenwoordigt configuratieobject voor apparaten. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | Specificeert soorten strategieën voor het schrijven van pagina's in output stream\streams. |

### Zie ook

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* naamruimte [Aspose.Html.Rendering](../../aspose.html.rendering/)
* montage [Aspose.HTML](../../)


