---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions clase. Representa la clase base para la implementación de dispositivos de representación particulares.
type: docs
weight: 4140
url: /es/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Representa la clase base para la implementación de dispositivos de representación particulares.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parámetro | Descripción |
| --- | --- |
| TGraphicContext | Contexto gráfico que contiene los parámetros de control de gráficos actuales |
| TRenderingOptions | Opciones de renderizado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | Obtiene el contexto gráfico |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | Obtiene opciones de renderizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | Agrega un rectángulo a la ruta actual como una subruta completa. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | Comienza a renderizar el documento. |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Comienza el renderizado del nodo. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | Comienza a renderizar la nueva página. |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | Modifica la ruta de recorte actual al intersectarla con la ruta actual, utilizando la regla FillMode para determinar la región a rellenar. Este método finaliza la ruta actual. |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | Cierra el subtrayecto actual agregando un segmento de línea recta desde el punto actual hasta el punto inicial del subtrayecto. Si la subruta actual ya está cerrada, "ClosePath" no hace nada. Este operador finaliza la subruta actual. Al agregar otro segmento a la ruta actual, comienza una nueva subruta, incluso si el nuevo segmento comienza en el punto final alcanzado por el método "ClosePath". |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Agrega una curva de Bézier cúbica a la ruta actual. La curva se extiende desde el punto actual hasta el punto pt2, utilizando pt1 y pt2 como puntos de control Bézier. El nuevo punto actual es pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | Dibuja la imagen especificada. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | Finaliza el renderizado del documento. |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | Finaliza el renderizado del nodo. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | Finaliza el renderizado de la página actual. |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | Rellena toda la región encerrada por la ruta actual. Si el camino consta de varios subcaminos desconectados, llena el interior de todos los subcaminos, considerados juntos. Este método finaliza la ruta actual. |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | Rellena la cadena de texto especificada en la ubicación especificada. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | Vacía todos los datos al flujo de salida. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | Agrega un segmento de línea recta desde el punto actual hasta el punto (pt). El nuevo punto actual es pt. |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | Comienza un nuevo subtrayecto moviendo el punto actual a las coordenadas del parámetro pt, omitiendo cualquier segmento de línea de conexión. Si el método de construcción de ruta anterior en la ruta actual también era "Mover a", el nuevo "Mover a" lo anula; no queda ningún vestigio de la operación anterior "Mover a" en la ruta. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | Restaura todo el contexto de gráficos a su valor anterior extrayéndolo de la pila. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | Inserta una copia de todo el contexto gráfico en la pila. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | Traza una línea a lo largo de la ruta actual. La línea trazada sigue cada segmento recto o curvo del camino, centrado en el segmento con lados paralelos a él. Cada uno de los subtrayectos de la ruta se trata por separado. Este método finaliza la ruta actual. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | Trazos y relleno de la ruta actual. Este método finaliza la ruta actual. |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | Traza la cadena de texto especificada en la ubicación especificada. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | Representa el objeto de configuración para dispositivos. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | Especifica tipos de estrategias para escribir páginas en el flujo de salida\flujos. |

### Ver también

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* espacio de nombres [Aspose.Html.Rendering](../../aspose.html.rendering/)
* asamblea [Aspose.HTML](../../)


