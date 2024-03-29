---
title: Interface IDevice
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Rendering.IDevice interfaz. Define métodos y propiedades que admiten la representación personalizada de elementos gráficos como rutas texto e imágenes.
type: docs
weight: 4280
url: /es/net/aspose.html.rendering/idevice/
---
## IDevice interface

Define métodos y propiedades que admiten la representación personalizada de elementos gráficos como rutas, texto e imágenes.

```csharp
public interface IDevice : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | Obtiene el contexto gráfico. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | Obtiene opciones de renderizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | Agrega un rectángulo a la ruta actual como una subruta completa. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | Comienza a renderizar el documento. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Comienza el renderizado del elemento. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | Comienza a renderizar la nueva página. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | Modifica la ruta de recorte actual al intersectarla con la ruta actual, utilizando la regla FillMode para determinar la región a rellenar. Este método finaliza la ruta actual. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | Cierra el subtrayecto actual agregando un segmento de línea recta desde el punto actual hasta el punto inicial del subtrayecto. Si la subruta actual ya está cerrada, "ClosePath" no hace nada. Este operador finaliza la subruta actual. Al agregar otro segmento a la ruta actual, comienza una nueva subruta, incluso si el nuevo segmento comienza en el punto final alcanzado por el método "ClosePath". |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Agrega una curva de Bézier cúbica a la ruta actual. La curva se extiende desde el punto actual hasta el punto pt3, utilizando pt1 y pt2 como puntos de control Bézier. El nuevo punto actual es pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | Dibuja la imagen especificada. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | Finaliza el renderizado del documento. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | Finaliza el renderizado del elemento. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | Finaliza el renderizado de la página actual. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | Rellena toda la región encerrada por la ruta actual. Si el camino consta de varios subcaminos desconectados, llena el interior de todos los subcaminos, considerados juntos. Este método finaliza la ruta actual. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | Rellena la cadena de texto especificada en la ubicación especificada. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | Vacía todos los datos al flujo de salida. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | Agrega un segmento de línea recta desde el punto actual hasta el punto (pt). El nuevo punto actual es pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | Comienza un nuevo subtrayecto moviendo el punto actual a las coordenadas del parámetro pt, omitiendo cualquier segmento de línea de conexión. Si el método de construcción de ruta anterior en la ruta actual también era "Mover a", el nuevo "Mover a" lo anula; no queda ningún vestigio de la operación anterior "Mover a" en la ruta. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | Restaura todo el contexto de gráficos a su valor anterior extrayéndolo de la pila. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | Inserta una copia de todo el contexto gráfico en la pila. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | Traza una línea a lo largo de la ruta actual. La línea trazada sigue cada segmento recto o curvo del camino, centrado en el segmento con lados paralelos a él. Cada uno de los subtrayectos de la ruta se trata por separado. Este método finaliza la ruta actual. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | Trazos y relleno de la ruta actual. Este método finaliza la ruta actual. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | Traza la cadena de texto especificada en la ubicación especificada. |

### Ver también

* espacio de nombres [Aspose.Html.Rendering](../../aspose.html.rendering/)
* asamblea [Aspose.HTML](../../)


