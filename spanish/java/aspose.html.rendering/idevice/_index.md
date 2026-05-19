---
title: "Interfaz IDevice"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Interfaz com.aspose.html.rendering.IDevice. Define métodos y propiedades que soportan el renderizado personalizado de los elementos gráficos como rutas, texto e imágenes"
type: docs

url: /es/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Define métodos y propiedades que soportan el renderizado personalizado de los elementos gráficos como rutas, texto e imágenes.

```java
public interface IDevice : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Obtiene el contexto gráfico. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Obtiene las opciones de renderizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Añade un rectángulo a la ruta actual como una subruta completa. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Comienza la renderización del documento. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Inicia el renderizado del elemento. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Comienza la renderización de la nueva página. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Modifica la ruta de recorte actual intersectándola con la ruta actual, usando la FillRule para determinar la región a rellenar. Este método finaliza la ruta actual. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Cierra la subruta actual añadiendo un segmento de línea recta desde el punto actual hasta el punto de inicio de la subruta. Si la subruta actual ya está cerrada, "ClosePath" no hace nada. Este operador termina la subruta actual. Añadir otro segmento a la ruta actual comienza una nueva subruta, incluso si el nuevo segmento comienza en el punto final alcanzado por el método "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Añade una curva cúbica de Bézier a la ruta actual. La curva se extiende desde el punto actual hasta el punto pt3, usando pt1 y pt2 como puntos de control de Bézier. El nuevo punto actual es pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Dibuja la imagen especificada. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Finaliza el renderizado del documento. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Finaliza el renderizado del elemento. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Finaliza la renderización de la página actual. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Rellena toda la región delimitada por la ruta actual. Si la ruta consta de varios subtrazados desconectados, rellena el interior de todos los subtrazados, considerados en conjunto. Este método finaliza la ruta actual. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Rellena la cadena de texto especificada en la ubicación especificada. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Vuelca todos los datos al flujo de salida. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Añade un segmento de línea recta desde el punto actual hasta el punto (pt). El nuevo punto actual es pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Comienza un nuevo subtrazo moviendo el punto actual a las coordenadas del parámetro pt, omitiendo cualquier segmento de línea de conexión. Si el método de construcción de ruta anterior en la ruta actual también era "MoveTo", el nuevo "MoveTo" lo sobrescribe; no queda rastro de la operación "MoveTo" anterior en la ruta. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Restaura todo el contexto gráfico a su valor anterior sacándolo de la pila. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Empuja una copia de todo el contexto gráfico a la pila. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Dibuja una línea a lo largo de la ruta actual. La línea trazada sigue cada segmento recto o curvo de la ruta, centrada en el segmento con los lados paralelos a él. Cada uno de los subtrazados de la ruta se trata por separado. Este método finaliza la ruta actual. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Dibuja y rellena la ruta actual. Este método finaliza la ruta actual. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Dibuja la cadena de texto especificada en la ubicación especificada. |

### Ver también

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
