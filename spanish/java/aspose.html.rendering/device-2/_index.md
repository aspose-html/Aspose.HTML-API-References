---
title: "Clase DeviceTGraphicContextTRenderingOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions. Representa la clase base para la implementación de dispositivos de renderizado particulares"
type: docs

url: /es/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Representa la clase base para la implementación de dispositivos de renderizado particulares.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parámetro | Descripción |
| --- | --- |
| TGraphicContext | Contexto gráfico que contiene los parámetros actuales de control gráfico |
| TRenderingOptions | Opciones de renderizado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Obtiene el contexto gráfico |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Obtiene las opciones de renderizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Añade un rectángulo a la ruta actual como una subruta completa. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Comienza la renderización del documento. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Inicia el renderizado del nodo. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Comienza la renderización de la nueva página. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Modifica la ruta de recorte actual intersectándola con la ruta actual, usando la FillRule para determinar la región a rellenar. Este método finaliza la ruta actual. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Cierra la subruta actual añadiendo un segmento de línea recta desde el punto actual hasta el punto de inicio de la subruta. Si la subruta actual ya está cerrada, "ClosePath" no hace nada. Este operador termina la subruta actual. Añadir otro segmento a la ruta actual comienza una nueva subruta, incluso si el nuevo segmento comienza en el punto final alcanzado por el método "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Añade una curva cúbica Bézier a la ruta actual. La curva se extiende desde el punto actual hasta el punto pt2, usando pt1 y pt2 como puntos de control Bézier. El nuevo punto actual es pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Dibuja la imagen especificada. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Finaliza el renderizado del documento. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Finaliza el renderizado del nodo. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Finaliza la renderización de la página actual. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Rellena toda la región delimitada por la ruta actual. Si la ruta consta de varios subtrazados desconectados, rellena el interior de todos los subtrazados, considerados en conjunto. Este método finaliza la ruta actual. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Rellena la cadena de texto especificada en la ubicación especificada. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Vuelca todos los datos al flujo de salida. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Añade un segmento de línea recta desde el punto actual hasta el punto (pt). El nuevo punto actual es pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Comienza un nuevo subtrazo moviendo el punto actual a las coordenadas del parámetro pt, omitiendo cualquier segmento de línea de conexión. Si el método de construcción de ruta anterior en la ruta actual también era "MoveTo", el nuevo "MoveTo" lo sobrescribe; no queda rastro de la operación "MoveTo" anterior en la ruta. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Restaura todo el contexto gráfico a su valor anterior sacándolo de la pila. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Empuja una copia de todo el contexto gráfico a la pila. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Dibuja una línea a lo largo de la ruta actual. La línea trazada sigue cada segmento recto o curvo de la ruta, centrada en el segmento con los lados paralelos a él. Cada uno de los subtrazados de la ruta se trata por separado. Este método finaliza la ruta actual. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Dibuja y rellena la ruta actual. Este método finaliza la ruta actual. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Dibuja la cadena de texto especificada en la ubicación especificada. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Especifica tipos de estrategias para escribir páginas en flujos de salida\\streams. |

### Ver también

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
