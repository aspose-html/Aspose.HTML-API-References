---
title: "Clase DocDevice"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.rendering.doc.DocDevice class. Representa la renderización a un documento DOCX."
type: docs

url: /es/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Representa el renderizado a un documento DOCX.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Inicializa una nueva instancia de la clase `DocDevice`. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Inicializa una nueva instancia de la clase `DocDevice` mediante flujo de salida. |
| [DocDevice](docdevice/#constructor_5)(String) | Inicializa una nueva instancia de la clase `DocDevice` mediante el nombre de archivo de salida. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Inicializa una nueva instancia de la clase `DocDevice` mediante opciones de renderizado y proveedor de flujo. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Inicializa una nueva instancia de la clase `DocDevice` mediante opciones de renderizado y flujo de salida. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Inicializa una nueva instancia de la clase `DocDevice` mediante opciones de renderizado y nombre de archivo de salida. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Añade un rectángulo a la ruta actual como una subruta completa. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Comienza la renderización del documento. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Comienza la renderización del nodo html. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Comienza la renderización de la nueva página. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Modifica la ruta de recorte actual intersectándola con la ruta actual, usando la regla FillMode para determinar la región a rellenar. Este método termina la ruta actual. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Cierra la subruta actual añadiendo un segmento de línea recta desde el punto actual hasta el punto de inicio de la subruta. Si la subruta actual ya está cerrada, "ClosePath" no hace nada. Este operador termina la subruta actual. Añadir otro segmento a la ruta actual comienza una nueva subruta, incluso si el nuevo segmento comienza en el punto final alcanzado por el método "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Añade una curva cúbica Bézier a la ruta actual. La curva se extiende desde el punto actual hasta el punto pt2, usando pt1 y pt2 como puntos de control Bézier. El nuevo punto actual es pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Dibuja la imagen especificada. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Finaliza la renderización del nodo html. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Finaliza el renderizado de la página actual. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Rellena toda la región delimitada por la ruta actual. Si la ruta consta de varios subtrazos desconectados, rellena el interior de todos los subtrazos, considerados en conjunto. Este método finaliza la ruta actual. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Rellena la cadena de texto especificada en la ubicación especificada. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Vierte todos los datos al flujo de salida. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Añade un segmento de línea recta desde el punto actual hasta el punto (pt). El nuevo punto actual es pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Comienza un nuevo subtrazo moviendo el punto actual a las coordenadas del parámetro pt, omitiendo cualquier segmento de línea de conexión. Si el método de construcción de ruta anterior en la ruta actual también era "MoveTo", el nuevo "MoveTo" lo sobrescribe; no queda rastro de la operación "MoveTo" anterior en la ruta. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Dibuja una línea a lo largo de la ruta actual. La línea trazada sigue cada segmento recto o curvo de la ruta, centrada en el segmento con los lados paralelos a él. Cada uno de los subtrazos de la ruta se trata por separado. Este método finaliza la ruta actual. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Dibuja y rellena la ruta actual. Este método finaliza la ruta actual. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Dibuja la cadena de texto especificada en la ubicación especificada. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Mantiene los parámetros de control gráfico actuales para el DocDevice. Estos parámetros definen el marco global dentro del cual se ejecutan los operadores gráficos. |

### Ver también

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
