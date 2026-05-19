---
title: "XpsDevice‑klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.xps.XpsDevice‑klasse. Vertegenwoordigt het renderen naar een XPS‑document."
type: docs

url: /nl/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Stelt het renderen naar een xps‑document voor.

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Initialiseert een nieuw exemplaar van de `XpsDevice`‑klasse. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Initialiseert een nieuw exemplaar van de `XpsDevice`‑klasse. |
| [XpsDevice](xpsdevice/#constructor_5)(String) | Initialiseert een nieuw exemplaar van de `XpsDevice`‑klasse. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initialiseert een nieuw exemplaar van de `XpsDevice`‑klasse met renderopties en stream‑provider. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Initialiseert een nieuw exemplaar van de `XpsDevice`‑klasse met renderopties en uitvoerstroom. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | Initialiseert een nieuw exemplaar van de `XpsDevice`‑klasse met renderopties en uitvoerbestandsnaam. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) |  |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) |  |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() |  |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) |  |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() |  |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) |  |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) |  |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() |  |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) |  |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) |  |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() |  |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) |  |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | Bevat de huidige grafische besturingsparameters voor de XpsDevice. Deze parameters definiëren het globale kader waarbinnen de grafische operatoren worden uitgevoerd. |

### Zie ook

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
