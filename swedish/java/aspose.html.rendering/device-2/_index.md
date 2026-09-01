---
title: "DeviceTGraphicContextTRenderingOptions klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions klass. Representerar basklass för implementering av specifika renderingsenheter"
type: docs

url: /sv/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Representerar basklass för implementering av specifika renderingsenheter.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Beskrivning |
| --- | --- |
| TGraphicContext | Grafisk kontext som innehåller aktuella grafikstyrningsparametrar |
| TRenderingOptions | Renderingsalternativ |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Hämtar den grafiska kontexten |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Hämtar renderingsalternativ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Lägger till en rektangel till den aktuella banan som en komplett underbana. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Påbörjar rendering av dokumentet. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Påbörjar rendering av noden. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Påbörjar rendering av den nya sidan. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Modifierar den aktuella beskärningsbanan genom att skära den med den aktuella banan, med FillRule för att bestämma området som ska fyllas. Denna metod avslutar den aktuella banan. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Stänger den aktuella underbanan genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för underbanan. Om den aktuella underbanan redan är stängd gör \"ClosePath\" inget. Denna operator avslutar den aktuella underbanan. Att lägga till ett annat segment till den aktuella banan startar en ny underbana, även om det nya segmentet börjar vid slutpunkten som nås av \"ClosePath\"‑metoden. |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Lägger till en kubisk Bézier‑kurva till den aktuella banan. Kurvan sträcker sig från den aktuella punkten till punkten pt2, med pt1 och pt2 som Bézier‑kontrollpunkter. Den nya aktuella punkten är pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Ritar den angivna bilden. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Avslutar rendering av dokumentet. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Avslutar rendering av noden. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Avslutar rendering av den aktuella sidan. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Fyller hela området som omsluts av den aktuella vägen. Om vägen består av flera separata delvägar fyller den insidan av alla delvägar, betraktade tillsammans. Denna metod avslutar den aktuella vägen. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Fyller den angivna textsträngen på den angivna platsen. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Spolar alla data till utströmmen. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya aktuella punkten är pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Påbörjar en ny delväg genom att flytta den aktuella punkten till koordinaterna för parametern pt, utan att lägga till något förbindelselinjesegment. Om den föregående väggenereringsmetoden i den aktuella vägen också var "MoveTo", så ersätter den nya "MoveTo" den; ingen spår av den tidigare "MoveTo"-operationen återstår i vägen. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Pushar en kopia av hela grafikkontexten på stacken. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Ritar en linje längs den aktuella vägen. Den ritade linjen följer varje rakt eller kurvat segment i vägen, centrerad på segmentet med sidor parallella med det. Varje av vägens delvägar behandlas separat. Denna metod avslutar den aktuella vägen. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Ritar och fyller den aktuella vägen. Denna metod avslutar den aktuella vägen. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Ritar den angivna textsträngen på den angivna platsen. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Anger typer av strategier för att skriva sidor till utdata\strömmar. |

### Se även

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
