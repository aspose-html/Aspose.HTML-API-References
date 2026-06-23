---
title: "IDevice-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.IDevice-gränssnitt. Definierar metoder och egenskaper som stödjer anpassad rendering av grafiska element som banor, text och bilder."
type: docs

url: /sv/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Definierar metoder och egenskaper som stödjer anpassad rendering av grafiska element som banor, text och bilder.

```java
public interface IDevice : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Hämtar den grafiska kontexten. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Hämtar renderingsalternativ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Lägger till en rektangel till den aktuella banan som en komplett underbana. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Påbörjar rendering av dokumentet. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Påbörjar rendering av elementet. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Påbörjar rendering av den nya sidan. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Modifierar den aktuella beskärningsbanan genom att skära den med den aktuella banan, med FillRule för att bestämma området som ska fyllas. Denna metod avslutar den aktuella banan. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Stänger den aktuella underbanan genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för underbanan. Om den aktuella underbanan redan är stängd gör \"ClosePath\" inget. Denna operator avslutar den aktuella underbanan. Att lägga till ett annat segment till den aktuella banan startar en ny underbana, även om det nya segmentet börjar vid slutpunkten som nås av \"ClosePath\"‑metoden. |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Lägger till en kubisk Bézier-kurva till den aktuella banan. Kurvan sträcker sig från den aktuella punkten till punkten pt3, med pt1 och pt2 som Bézier-kontrollpunkter. Den nya aktuella punkten är pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Ritar den angivna bilden. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Avslutar rendering av dokumentet. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Avslutar rendering av elementet. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Avslutar rendering av den aktuella sidan. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Fyller hela området som omsluts av den aktuella vägen. Om vägen består av flera separata delvägar fyller den insidan av alla delvägar, betraktade tillsammans. Denna metod avslutar den aktuella vägen. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Fyller den angivna textsträngen på den angivna platsen. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Spolar alla data till utströmmen. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya aktuella punkten är pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Påbörjar en ny delväg genom att flytta den aktuella punkten till koordinaterna för parametern pt, utan att lägga till något förbindelselinjesegment. Om den föregående väggenereringsmetoden i den aktuella vägen också var "MoveTo", så ersätter den nya "MoveTo" den; ingen spår av den tidigare "MoveTo"-operationen återstår i vägen. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Pushar en kopia av hela grafikkontexten på stacken. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Ritar en linje längs den aktuella vägen. Den ritade linjen följer varje rakt eller kurvat segment i vägen, centrerad på segmentet med sidor parallella med det. Varje av vägens delvägar behandlas separat. Denna metod avslutar den aktuella vägen. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Ritar och fyller den aktuella vägen. Denna metod avslutar den aktuella vägen. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Ritar den angivna textsträngen på den angivna platsen. |

### Se även

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
