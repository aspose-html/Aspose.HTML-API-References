---
title: "ImageDevice klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.image.ImageDevice klass. Representerar rendering till rasterformat jpeg png bmp gif tiff."
type: docs

url: /sv/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Representerar rendering till rasterformat: jpeg, png, bmp, gif, tiff.

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Initierar en ny instans av `ImageDevice`-klassen. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Initierar en ny instans av `ImageDevice`-klassen. |
| [ImageDevice](imagedevice/#constructor_5)(String) | Initierar en ny instans av `ImageDevice`-klassen. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Initierar en ny instans av klassen `ImageDevice` med renderingsalternativ och strömleverantör. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Initierar en ny instans av klassen `ImageDevice` med renderingsalternativ och utdataström. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | Initierar en ny instans av klassen `ImageDevice` med renderingsalternativ och utdatafilnamn. |

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
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | Innehåller aktuella grafikstyrningsparametrar för `ImageDevice`. Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna körs. |

### Se även

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
