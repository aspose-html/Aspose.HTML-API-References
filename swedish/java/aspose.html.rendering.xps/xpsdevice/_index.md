---
title: "XpsDevice‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.xps.XpsDevice‑klass. Representerar rendering till ett xps‑dokument"
type: docs

url: /sv/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Representerar rendering till ett XPS‑dokument.

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Initierar en ny instans av `XpsDevice`‑klassen. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Initierar en ny instans av `XpsDevice`‑klassen. |
| [XpsDevice](xpsdevice/#constructor_5)(String) | Initierar en ny instans av `XpsDevice`‑klassen. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initierar en ny instans av `XpsDevice`‑klassen med renderingsalternativ och strömleverantör. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Initierar en ny instans av `XpsDevice`‑klassen med renderingsalternativ och utdataström. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | Initierar en ny instans av `XpsDevice`‑klassen med renderingsalternativ och utdatafilnamn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Metoder

| Namn | Beskrivning |
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

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | Innehåller aktuella grafikstyrningsparametrar för XpsDevice. Dessa parametrar definierar den globala ramen inom vilken grafikoperatorerna körs. |

### Se även

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
