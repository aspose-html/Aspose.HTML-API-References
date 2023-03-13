---
title: Interface IDevice
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Rendering.IDevice koppel. Definieert methoden en eigenschappen die aangepaste weergave van de grafische elementen zoals paden tekst en afbeeldingen ondersteunen.
type: docs
weight: 4280
url: /nl/net/aspose.html.rendering/idevice/
---
## IDevice interface

Definieert methoden en eigenschappen die aangepaste weergave van de grafische elementen zoals paden, tekst en afbeeldingen ondersteunen.

```csharp
public interface IDevice : IDisposable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | Krijgt de grafische context. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | Krijgt weergave-opties. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | Voegt een rechthoek toe aan het huidige pad als een volledig subpad. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | Begint met het renderen van het document. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Begint met renderen van het element. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | Begint met renderen van de nieuwe pagina. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | Wijzigt het huidige uitknippad door het te kruisen met het huidige pad, waarbij de FillMode-regel wordt gebruikt om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | Sluit het huidige subpad door een recht lijnstuk toe te voegen vanaf het huidige punt naar het beginpunt van het subpad. Als het huidige subpad al gesloten is, doet "ClosePath" niets. Deze operator beëindigt het huidige subpad. Door nog een segment aan het huidige pad toe te voegen, begint een nieuw subpad, , zelfs als het nieuwe segment begint bij het eindpunt dat wordt bereikt door de "ClosePath"-methode. |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve strekt zich uit van het huidige punt tot het punt pt3, met pt1 en pt2 als de Bézier-controlepunten. Het nieuwe huidige punt is pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | Tekent de opgegeven afbeelding. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | Beëindigt de weergave van het document. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | Beëindigt het renderen van het element. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | Vult het hele gebied dat wordt ingesloten door het huidige pad. Als het pad uit meerdere niet-verbonden subpaden bestaat, vult het de binnenkant van alle subpaden, samen beschouwd. Deze methode beëindigt het huidige pad. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | Vult de opgegeven tekenreeks op de opgegeven locatie. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | Spoelt alle gegevens naar uitvoerstroom. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | Voegt een recht lijnstuk toe vanaf het huidige punt aan het punt (pt). Het nieuwe huidige punt is pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, waarbij elk verbindingslijnsegment wordt weggelaten. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; geen overblijfsel van de vorige "MoveTo"-bewerking blijft in het pad. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze uit de stapel te halen. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | Duwt een kopie van de volledige grafische context naar de stapel. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | Trekt een lijn langs het huidige pad. De gestreepte lijn volgt elk recht of gebogen segment in het pad, gecentreerd op het segment met evenwijdige zijden. Elk van de subpaden van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | Lijnt en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | Lijnt de gespecificeerde tekstreeks uit op de gespecificeerde locatie. |

### Zie ook

* naamruimte [Aspose.Html.Rendering](../../aspose.html.rendering/)
* montage [Aspose.HTML](../../)


