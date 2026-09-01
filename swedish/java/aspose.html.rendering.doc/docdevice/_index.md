---
title: "DocDevice Class"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.doc.DocDevice class. Representerar rendering till ett DOCX‑dokument"
type: docs

url: /sv/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Representerar rendering till ett DOCX‑dokument.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initierar en ny instans av klassen `DocDevice`. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initierar en ny instans av klassen `DocDevice` via utström. |
| [DocDevice](docdevice/#constructor_5)(String) | Initierar en ny instans av klassen `DocDevice` via utfilens namn. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initierar en ny instans av klassen `DocDevice` med renderingsalternativ och strömleverantör. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initierar en ny instans av klassen `DocDevice` med renderingsalternativ och utström. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Initierar en ny instans av klassen `DocDevice` med renderingsalternativ och utfilens namn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Lägger till en rektangel till den aktuella banan som en komplett underbana. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Påbörjar rendering av dokumentet. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Påbörjar rendering av html‑noden. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Påbörjar rendering av den nya sidan. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Modifierar den aktuella klippningsbanan genom att skära den med den aktuella banan, med FillMode‑regeln för att bestämma området som ska fyllas. Denna metod avslutar den aktuella banan. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Stänger den aktuella underbanan genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för underbanan. Om den aktuella underbanan redan är stängd gör \"ClosePath\" inget. Denna operator avslutar den aktuella underbanan. Att lägga till ett annat segment till den aktuella banan startar en ny underbana, även om det nya segmentet börjar vid slutpunkten som nås av \"ClosePath\"‑metoden. |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Lägger till en kubisk Bézier‑kurva till den aktuella banan. Kurvan sträcker sig från den aktuella punkten till punkten pt2, med pt1 och pt2 som Bézier‑kontrollpunkter. Den nya aktuella punkten är pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Ritar den angivna bilden. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Avslutar rendering av html‑noden. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Avslutar rendering av den aktuella sidan. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Fyller hela området som omsluts av den aktuella vägen. Om vägen består av flera separata delvägar fyller den insidan av alla delvägar, betraktade tillsammans. Denna metod avslutar den aktuella vägen. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Fyller den angivna textsträngen på den angivna platsen. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Spolar alla data till utströmmen. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya aktuella punkten är pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Påbörjar en ny delväg genom att flytta den aktuella punkten till koordinaterna för parametern pt, utan att lägga till något förbindelselinjesegment. Om den föregående väggenereringsmetoden i den aktuella vägen också var "MoveTo", så ersätter den nya "MoveTo" den; ingen spår av den tidigare "MoveTo"-operationen återstår i vägen. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Ritar en linje längs den aktuella vägen. Den ritade linjen följer varje rakt eller kurvat segment i vägen, centrerad på segmentet med sidor parallella med det. Varje av vägens delvägar behandlas separat. Denna metod avslutar den aktuella vägen. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Ritar och fyller den aktuella vägen. Denna metod avslutar den aktuella vägen. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Ritar den angivna textsträngen på den angivna platsen. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Behåller de aktuella grafikstyrningsparametrarna för DocDevice. Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna körs. |

### Se även

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
