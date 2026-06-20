---
title: "ImageDevice Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.image.ImageDevice Klasse. Stellt das Rendern in Rasterformate jpeg png bmp gif tiff dar."
type: docs

url: /de/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Stellt das Rendern in Rasterformate dar: jpeg, png, bmp, gif, tiff.

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Initialisiert eine neue Instanz der `ImageDevice` Klasse. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Initialisiert eine neue Instanz der `ImageDevice` Klasse. |
| [ImageDevice](imagedevice/#constructor_5)(String) | Initialisiert eine neue Instanz der `ImageDevice` Klasse. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Initialisiert eine neue Instanz der `ImageDevice`-Klasse mit Rendering-Optionen und Stream-Provider. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Initialisiert eine neue Instanz der `ImageDevice`-Klasse mit Rendering-Optionen und Ausgabestream. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | Initialisiert eine neue Instanz der `ImageDevice`-Klasse mit Rendering-Optionen und Ausgabedateinamen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Methoden

| Name | Beschreibung |
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

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | Enthält aktuelle Grafiksteuerungsparameter für das `ImageDevice`. Diese Parameter definieren den globalen Rahmen, innerhalb dessen die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
