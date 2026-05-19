---
title: "Clase XpsDevice"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.rendering.xps.XpsDevice. Representa la renderización a un documento xps"
type: docs

url: /es/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Representa el renderizado a un documento xps.

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Inicializa una nueva instancia de la clase `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Inicializa una nueva instancia de la clase `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_5)(String) | Inicializa una nueva instancia de la clase `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Inicializa una nueva instancia de la clase `XpsDevice` mediante opciones de renderizado y proveedor de flujo. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Inicializa una nueva instancia de la clase `XpsDevice` mediante opciones de renderizado y flujo de salida. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | Inicializa una nueva instancia de la clase `XpsDevice` mediante opciones de renderizado y nombre de archivo de salida. |

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
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | Mantiene los parámetros actuales de control gráfico para el XpsDevice. Estos parámetros definen el marco global dentro del cual se ejecutan los operadores gráficos. |

### Ver también

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
