---
title: "PdfDevice Clase"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.rendering.pdf.PdfDevice clase. Representa el renderizado a un documento pdf"
type: docs

url: /es/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Representa el renderizado a un documento PDF.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Inicializa una nueva instancia de la clase `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Inicializa una nueva instancia de la clase `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | Inicializa una nueva instancia de la clase `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Inicializa una nueva instancia de la clase `PdfDevice` mediante opciones de renderizado y proveedor de flujo. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Inicializa una nueva instancia de la clase `PdfDevice` mediante opciones de renderizado y flujo de salida. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | Inicializa una nueva instancia de la clase `PdfDevice` mediante opciones de renderizado y nombre de archivo de salida. |

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
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Mantiene los parámetros actuales de control gráfico para el PdfDevice. Estos parámetros definen el marco global dentro del cual se ejecutan los operadores gráficos. |

### Ver también

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
