---
title: PdfDevice
second_title: Справочник по Aspose.HTML для .NET API
description: Представляет рендеринг в PDF-документ.
type: docs
weight: 4510
url: /ru/net/aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Представляет рендеринг в PDF-документ.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfDevice](pdfdevice#constructor)(ICreateStreamProvider) | Инициализирует новый экземпляр класса[`PdfDevice`](../pdfdevice). |
| [PdfDevice](pdfdevice#constructor_4)(Stream) | Инициализирует новый экземпляр класса[`PdfDevice`](../pdfdevice). |
| [PdfDevice](pdfdevice#constructor_5)(string) | Инициализирует новый экземпляр класса[`PdfDevice`](../pdfdevice). |
| [PdfDevice](pdfdevice#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Инициализирует новый экземпляр класса[`PdfDevice`](../pdfdevice)с помощью параметров рендеринга и поставщика потоков. |
| [PdfDevice](pdfdevice#constructor_2)(PdfRenderingOptions, Stream) | Инициализирует новый экземпляр класса[`PdfDevice`](../pdfdevice)с помощью параметров рендеринга и выходного потока. |
| [PdfDevice](pdfdevice#constructor_3)(PdfRenderingOptions, string) | Инициализирует новый экземпляр класса[`PdfDevice`](../pdfdevice)с параметрами рендеринга и именем выходного файла. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.html.rendering/device`2/options) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.pdf/pdfdevice/addrect)(RectangleF) | Добавляет прямоугольник к текущему пути как полный подпуть. |
| override [BeginDocument](../../aspose.html.rendering.pdf/pdfdevice/begindocument)(Document) | Начинает визуализацию документа. |
| override [BeginElement](../../aspose.html.rendering.pdf/pdfdevice/beginelement)(Element, RectangleF) | Начинает визуализацию элемента. |
| override [BeginPage](../../aspose.html.rendering.pdf/pdfdevice/beginpage)(SizeF) | Начинает рендеринг новой страницы. |
| override [Clip](../../aspose.html.rendering.pdf/pdfdevice/clip)(FillMode) | Изменяет текущий путь отсечения, пересекая его с текущим путем, используя правило FillMode для определения области для заполнения. Этот метод завершает текущий путь. |
| override [ClosePath](../../aspose.html.rendering.pdf/pdfdevice/closepath)() | Закрывает текущий подконтур, добавляя отрезок прямой линии от текущей точки до начальной точки подконтура. Если текущий подпуть уже закрыт, "ClosePath" ничего не делает. Этот оператор завершает текущий подпуть. При добавлении другого сегмента к текущему пути начинается новый подпуть, , даже если новый сегмент начинается в конечной точке, достигнутой методом ClosePath. |
| override [CubicBezierTo](../../aspose.html.rendering.pdf/pdfdevice/cubicbezierto)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая продолжается от текущей точки до точки pt2, с использованием pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка - pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.html.rendering.pdf/pdfdevice/drawimage)(byte[], ImageType, RectangleF) | Рисует указанное изображение. |
| override [EndDocument](../../aspose.html.rendering.pdf/pdfdevice/enddocument)() | Завершает визуализацию документа. |
| override [EndElement](../../aspose.html.rendering.pdf/pdfdevice/endelement)(Element) | Завершает визуализацию элемента. |
| override [EndPage](../../aspose.html.rendering.pdf/pdfdevice/endpage)() | Завершает визуализацию текущей страницы. |
| override [Fill](../../aspose.html.rendering.pdf/pdfdevice/fill)(FillMode) | Заполняет всю область, ограниченную текущим путем. Если путь состоит из нескольких несвязанных подпутей, он заполняет внутренности всех подпутей, рассматриваемых вместе. Этот метод завершает текущий путь. |
| override [FillText](../../aspose.html.rendering.pdf/pdfdevice/filltext)(string, PointF) | Заполняет указанную текстовую строку в указанном месте. |
| override [Flush](../../aspose.html.rendering.pdf/pdfdevice/flush)() | Сбрасывает все данные в выходной поток. |
| override [LineTo](../../aspose.html.rendering.pdf/pdfdevice/lineto)(PointF) | Добавляет отрезок прямой из текущей точки в точку (pt). Новая текущая точка - pt. |
| override [MoveTo](../../aspose.html.rendering.pdf/pdfdevice/moveto)(PointF) | Начинает новый подконтур, перемещая текущую точку в координаты параметра pt, опуская любой соединительный отрезок. Если предыдущий метод построения пути в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; на пути не осталось следов предыдущей операции "MoveTo". |
| override [RestoreGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/restoregraphiccontext)() | Восстанавливает весь графический контекст до его прежнего значения, выталкивая его из стека. |
| override [SaveGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/savegraphiccontext)() | Помещает в стек копию всего графического контекста. |
| override [Stroke](../../aspose.html.rendering.pdf/pdfdevice/stroke)() | Проводит линию по текущему пути. Заштрихованная линия следует за каждым прямым или изогнутым сегментом пути, с центром в сегменте со сторонами, параллельными ему. Каждый из подпутей пути обрабатывается отдельно. Этот метод завершает текущий путь. |
| override [StrokeAndFill](../../aspose.html.rendering.pdf/pdfdevice/strokeandfill)(FillMode) | Штрихи и заливка текущего пути. Этот метод завершает текущий путь. |
| override [StrokeText](../../aspose.html.rendering.pdf/pdfdevice/stroketext)(string, PointF) | Перемещает указанную текстовую строку в указанном месте. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [PdfGraphicContext](pdfdevice.pdfgraphiccontext) | Содержит текущие параметры управления графикой для PdfDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы. |

### Смотрите также

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext)
* class [PdfRenderingOptions](../pdfrenderingoptions)
* пространство имен [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
