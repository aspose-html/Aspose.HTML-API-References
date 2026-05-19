---
title: "DocDevice Class"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.doc.DocDevice class. Vertegenwoordigt rendering naar een DOCX-document"
type: docs

url: /nl/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Stelt het renderen naar een DOCX-document voor.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initialiseert een nieuw exemplaar van de `DocDevice`-klasse. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initialiseert een nieuw exemplaar van de `DocDevice`-klasse via een uitvoerstroom. |
| [DocDevice](docdevice/#constructor_5)(String) | Initialiseert een nieuw exemplaar van de `DocDevice`-klasse via een uitvoerbestandsnaam. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initialiseert een nieuw exemplaar van de `DocDevice`-klasse met renderopties en streamprovider. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initialiseert een nieuw exemplaar van de `DocDevice`-klasse met renderopties en uitvoerstroom. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Initialiseert een nieuw exemplaar van de `DocDevice`-klasse met renderopties en uitvoerbestandsnaam. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Voegt een rechthoek toe aan het huidige pad als een volledige subpad. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Begint met het renderen van het document. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Begint met het renderen van de html-node. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Begint met het renderen van de nieuwe pagina. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Wijzigt het huidige knippad door het te kruisen met het huidige pad, waarbij de FillMode-regel wordt gebruikt om het te vullen gebied te bepalen. Deze methode beëindigt het huidige pad. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Sluit het huidige subpad door een rechte lijnsegment toe te voegen van het huidige punt naar het startpunt van het subpad. Als het huidige subpad al gesloten is, doet \"ClosePath\" niets. Deze operator beëindigt het huidige subpad. Het toevoegen van een ander segment aan het huidige pad start een nieuw subpad, zelfs als het nieuwe segment begint bij het eindpunt dat door de \"ClosePath\"-methode is bereikt. |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Voegt een kubieke Bézier-curve toe aan het huidige pad. De curve loopt van het huidige punt naar punt pt2, met pt1 en pt2 als Bézier‑controlepunten. Het nieuwe huidige punt is pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Tekent de opgegeven afbeelding. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Beëindigt het renderen van de html-node. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Beëindigt het renderen van de huidige pagina. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Vult het volledige gebied dat door het huidige pad wordt omsloten. Als het pad bestaat uit meerdere losgekoppelde subpaden, vult het de binnenkant van alle subpaden, samen beschouwd. Deze methode beëindigt het huidige pad. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Vult de opgegeven tekststring op de opgegeven locatie. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Schrijft alle gegevens naar de uitvoerstroom. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Voegt een rechte lijnsegment toe van het huidige punt naar het punt (pt). Het nieuwe huidige punt is pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Begint een nieuw subpad door het huidige punt te verplaatsen naar de coördinaten van de parameter pt, zonder een verbindingslijnsegment. Als de vorige padconstructiemethode in het huidige pad ook "MoveTo" was, overschrijft de nieuwe "MoveTo" deze; er blijft geen spoor van de vorige "MoveTo"-operatie in het pad. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Tekent een lijn langs het huidige pad. De getekende lijn volgt elk rechte of gebogen segment in het pad, gecentreerd op het segment met zijden die er evenwijdig aan zijn. Elk van de subpaden van het pad wordt afzonderlijk behandeld. Deze methode beëindigt het huidige pad. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Tekent en vult het huidige pad. Deze methode beëindigt het huidige pad. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Tekent de opgegeven tekststring op de opgegeven locatie. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Bevat de huidige grafische controleparameters voor de DocDevice. Deze parameters definiëren het globale kader waarbinnen de grafische operatoren worden uitgevoerd. |

### Zie ook

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
