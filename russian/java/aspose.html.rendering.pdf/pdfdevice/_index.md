---
title: "Класс PdfDevice"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.pdf.PdfDevice. Представляет рендеринг в PDF‑документ"
type: docs

url: /ru/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Представляет рендеринг в PDF‑документ.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Инициализирует новый экземпляр класса `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Инициализирует новый экземпляр класса `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | Инициализирует новый экземпляр класса `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Инициализирует новый экземпляр класса `PdfDevice` с параметрами рендеринга и поставщиком потока. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Инициализирует новый экземпляр класса `PdfDevice` с параметрами рендеринга и выходным потоком. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | Инициализирует новый экземпляр класса `PdfDevice` с параметрами рендеринга и именем выходного файла. |

## Свойства

| Имя | Описание |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Методы

| Имя | Описание |
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

## Другие члены

| Имя | Описание |
| --- | --- |
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Содержит текущие параметры управления графикой для PdfDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы. |

### См. также

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
