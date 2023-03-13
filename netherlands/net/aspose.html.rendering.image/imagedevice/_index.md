---
title: Class ImageDevice
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Rendering.Image.ImageDevice klas. Vertegenwoordigt rendering naar rasterformaten jpeg png bmp gif tiff.
type: docs
weight: 4300
url: /nl/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Vertegenwoordigt rendering naar rasterformaten: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Initialiseert een nieuw exemplaar van het`ImageDevice` klasse. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Initialiseert een nieuw exemplaar van het`ImageDevice` klasse. |
| [ImageDevice](imagedevice/#constructor_5)(string) | Initialiseert een nieuw exemplaar van het`ImageDevice` klasse. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Initialiseert een nieuw exemplaar van het`ImageDevice` klasse door weergaveopties en streamprovider. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Initialiseert een nieuw exemplaar van het`ImageDevice`klasse door opties en uitvoerstroom weer te geven. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | Initialiseert een nieuw exemplaar van het`ImageDevice` klasse door weergaveopties en uitvoerbestandsnaam. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Haalt de instantie van Graphics. op |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | Voegt een rechthoek toe aan het huidige pad als een volledig subpad. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | Begint met het renderen van het document. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | Begint met renderen van het element. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | Begint met renderen van de nieuwe pagina. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | Wijzigt het huidige uitknippad door het te kruisen met het huidige pad, waarbij de FillMode-regel wordt gebruikt om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | Sluit het huidige subpad door een recht lijnstuk toe te voegen vanaf het huidige punt naar het beginpunt van het subpad. Als het huidige subpad al gesloten is, doet "ClosePath" niets. Deze operator beëindigt het huidige subpad. Door nog een segment aan het huidige pad toe te voegen, begint een nieuw subpad, , zelfs als het nieuwe segment begint bij het eindpunt dat wordt bereikt door de "ClosePath"-methode. |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve loopt van het huidige punt naar het punt pt2, met pt1 en pt2 als de Bézier-controlepunten. Het nieuwe huidige punt is pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | Tekent de opgegeven afbeelding. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | Beëindigt de weergave van het document. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | Beëindigt het renderen van het element. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | Vult het hele gebied dat wordt ingesloten door het huidige pad. Als het pad uit meerdere niet-verbonden subpaden bestaat, vult het de binnenkant van alle subpaden, samen beschouwd. Deze methode beëindigt het huidige pad. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | Vult de opgegeven tekenreeks op de opgegeven locatie. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | Spoelt alle gegevens naar uitvoerstroom. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | Voegt een recht lijnstuk toe vanaf het huidige punt aan het punt (pt). Het nieuwe huidige punt is pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, waarbij elk verbindingslijnsegment wordt weggelaten. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; geen overblijfsel van de vorige "MoveTo"-bewerking blijft in het pad. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze uit de stapel te halen. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | Duwt een kopie van de volledige grafische context naar de stapel. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | Trekt een lijn langs het huidige pad. De gestreepte lijn volgt elk recht of gebogen segment in het pad, gecentreerd op het segment met evenwijdige zijden. Elk van de subpaden van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | Lijnt en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | Lijnt de gespecificeerde tekstreeks uit op de gespecificeerde locatie. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | Bevat de huidige grafische besturingsparameters voor de`ImageDevice` . Deze parameters definiëren het globale raamwerk waarbinnen de grafische operators uitvoeren. |

### Zie ook

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* naamruimte [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* montage [Aspose.HTML](../../)


