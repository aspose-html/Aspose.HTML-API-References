---
title: "IDevice-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.IDevice-interface. Definieert methoden en eigenschappen die aangepaste weergave van grafische elementen zoals paden, tekst en afbeeldingen ondersteunen."
type: docs

url: /nl/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Definieert methoden en eigenschappen die aangepaste weergave van grafische elementen zoals paden, tekst en afbeeldingen ondersteunen.

```java
public interface IDevice : IDisposable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Haalt de grafische context op. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Haalt renderopties op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Voegt een rechthoek toe aan het huidige pad als een volledige subpad. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Begint met het renderen van het document. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Begint met het renderen van het element. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Begint met het renderen van de nieuwe pagina. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Wijzigt het huidige knippad door het te kruisen met het huidige pad, met behulp van de FillRule om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Sluit het huidige subpad door een rechte lijnsegment toe te voegen van het huidige punt naar het startpunt van het subpad. Als het huidige subpad al gesloten is, doet \"ClosePath\" niets. Deze operator beëindigt het huidige subpad. Het toevoegen van een ander segment aan het huidige pad start een nieuw subpad, zelfs als het nieuwe segment begint bij het eindpunt dat door de \"ClosePath\"-methode is bereikt. |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve loopt van het huidige punt naar punt pt3, met pt1 en pt2 als Bézier-controlepunten. Het nieuwe huidige punt is pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Tekent de opgegeven afbeelding. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Beëindigt het renderen van het document. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Beëindigt het renderen van het element. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Vult het volledige gebied dat door het huidige pad wordt omsloten. Als het pad bestaat uit meerdere losgekoppelde subpaden, vult het de binnenkant van alle subpaden, samen beschouwd. Deze methode beëindigt het huidige pad. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Vult de opgegeven tekststring op de opgegeven locatie. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Schrijft alle gegevens naar de uitvoerstroom. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Voegt een rechte lijnsegment toe van het huidige punt naar het punt (pt). Het nieuwe huidige punt is pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, zonder een verbindingslijnsegment. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; er blijft geen spoor van de vorige "MoveTo"-operatie in het pad. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Herstelt de volledige grafische context naar de vorige waarde door deze van de stack te halen. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Zet een kopie van de volledige grafische context op de stack. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Tekent een lijn langs het huidige pad. De getekende lijn volgt elk rechte of gebogen segment in het pad, gecentreerd op het segment met zijden die er evenwijdig aan zijn. Elk van de subpaden van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Tekent en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Tekent de opgegeven tekststring op de opgegeven locatie. |

### Zie ook

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
