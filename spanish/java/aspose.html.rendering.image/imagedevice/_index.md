---
title: "Clase ImageDevice"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.rendering.image.ImageDevice. Representa la renderización a formatos raster jpeg png bmp gif tiff."
type: docs

url: /es/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Representa el renderizado a formatos raster: jpeg, png, bmp, gif, tiff.

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Inicializa una nueva instancia de la clase `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Inicializa una nueva instancia de la clase `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_5)(String) | Inicializa una nueva instancia de la clase `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Inicializa una nueva instancia de la clase `ImageDevice` mediante opciones de renderizado y proveedor de flujo. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Inicializa una nueva instancia de la clase `ImageDevice` mediante opciones de renderizado y flujo de salida. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | Inicializa una nueva instancia de la clase `ImageDevice` mediante opciones de renderizado y nombre de archivo de salida. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Métodos

| Nombre | Descripción |
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

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | Mantiene los parámetros de control gráfico actuales para el `ImageDevice`. Estos parámetros definen el marco global dentro del cual se ejecutan los operadores gráficos. |

### Ver también

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
