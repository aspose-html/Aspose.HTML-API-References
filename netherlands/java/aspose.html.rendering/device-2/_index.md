---
title: "DeviceTGraphicContextTRenderingOptions Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions klasse. Vertegenwoordigt de basisklasse voor de implementatie van specifieke renderapparaten"
type: docs

url: /nl/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Stelt een basisklasse voor voor de implementatie van specifieke renderapparaten.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Beschrijving |
| --- | --- |
| TGraphicContext | Grafische context die de huidige grafische controleparameters bevat |
| TRenderingOptions | Renderopties |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Haalt de grafische context op |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Haalt renderopties op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Voegt een rechthoek toe aan het huidige pad als een volledige subpad. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Begint met het renderen van het document. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Begint met het renderen van het knooppunt. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Begint met het renderen van de nieuwe pagina. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Wijzigt het huidige knippad door het te kruisen met het huidige pad, met behulp van de FillRule om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Sluit het huidige subpad door een rechte lijnsegment toe te voegen van het huidige punt naar het startpunt van het subpad. Als het huidige subpad al gesloten is, doet \"ClosePath\" niets. Deze operator beëindigt het huidige subpad. Het toevoegen van een ander segment aan het huidige pad start een nieuw subpad, zelfs als het nieuwe segment begint bij het eindpunt dat door de \"ClosePath\"-methode is bereikt. |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve loopt van het huidige punt naar punt pt2, met pt1 en pt2 als Bézier‑controlepunten. Het nieuwe huidige punt is pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Tekent de opgegeven afbeelding. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Beëindigt het renderen van het document. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Beëindigt het renderen van het knooppunt. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Vult het volledige gebied dat door het huidige pad wordt omsloten. Als het pad bestaat uit meerdere losgekoppelde subpaden, vult het de binnenkant van alle subpaden, samen beschouwd. Deze methode beëindigt het huidige pad. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Vult de opgegeven tekststring op de opgegeven locatie. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Schrijft alle gegevens naar de uitvoerstroom. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Voegt een rechte lijnsegment toe van het huidige punt naar het punt (pt). Het nieuwe huidige punt is pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, zonder een verbindingslijnsegment. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; er blijft geen spoor van de vorige "MoveTo"-operatie in het pad. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze van de stack te halen. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Zet een kopie van de volledige grafische context op de stack. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Tekent een lijn langs het huidige pad. De getekende lijn volgt elk rechte of gebogen segment in het pad, gecentreerd op het segment met zijden die er evenwijdig aan zijn. Elk van de subpaden van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Tekent en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Tekent de opgegeven tekststring op de opgegeven locatie. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Specificeert soorten strategieën voor het schrijven van pagina's naar output stream\\streams. |

### Zie ook

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
