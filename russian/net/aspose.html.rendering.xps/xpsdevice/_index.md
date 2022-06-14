---
title: XpsDevice
second_title: Справочник по Aspose.HTML для .NET API
description: Представляет рендеринг в документ XPS.
type: docs
weight: 4600
url: /ru/net/aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Представляет рендеринг в документ XPS.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XpsDevice](xpsdevice#constructor)(ICreateStreamProvider) | Инициализирует новый экземпляр класса[`XpsDevice`](../xpsdevice). |
| [XpsDevice](xpsdevice#constructor_4)(Stream) | Инициализирует новый экземпляр класса[`XpsDevice`](../xpsdevice). |
| [XpsDevice](xpsdevice#constructor_5)(string) | Инициализирует новый экземпляр класса[`XpsDevice`](../xpsdevice). |
| [XpsDevice](xpsdevice#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Инициализирует новый экземпляр класса[`XpsDevice`](../xpsdevice)с помощью параметров рендеринга и поставщика потоков. |
| [XpsDevice](xpsdevice#constructor_2)(XpsRenderingOptions, Stream) | Инициализирует новый экземпляр класса[`XpsDevice`](../xpsdevice)с помощью параметров рендеринга и выходного потока. |
| [XpsDevice](xpsdevice#constructor_3)(XpsRenderingOptions, string) | Инициализирует новый экземпляр класса[`XpsDevice`](../xpsdevice)с параметрами рендеринга и именем выходного файла. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.html.rendering/device`2/options) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.xps/xpsdevice/addrect)(RectangleF) | Добавляет прямоугольник к текущему пути как полный подпуть. |
| override [BeginDocument](../../aspose.html.rendering.xps/xpsdevice/begindocument)(Document) | Начинает визуализацию документа. |
| override [BeginElement](../../aspose.html.rendering.xps/xpsdevice/beginelement)(Element, RectangleF) | Начинает визуализацию элемента. |
| override [BeginPage](../../aspose.html.rendering.xps/xpsdevice/beginpage)(SizeF) | Начинает рендеринг новой страницы. |
| override [Clip](../../aspose.html.rendering.xps/xpsdevice/clip)(FillMode) | Изменяет текущий путь отсечения, пересекая его с текущим путем, используя правило FillMode для определения области для заполнения. Этот метод завершает текущий путь. |
| override [ClosePath](../../aspose.html.rendering.xps/xpsdevice/closepath)() | Закрывает текущий подконтур, добавляя отрезок прямой линии от текущей точки до начальной точки подконтура. Если текущий подпуть уже закрыт, "ClosePath" ничего не делает. Этот оператор завершает текущий подпуть. При добавлении другого сегмента к текущему пути начинается новый подпуть, , даже если новый сегмент начинается в конечной точке, достигнутой методом ClosePath. |
| override [CubicBezierTo](../../aspose.html.rendering.xps/xpsdevice/cubicbezierto)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая продолжается от текущей точки до точки pt2, с использованием pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка - pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.html.rendering.xps/xpsdevice/drawimage)(byte[], ImageType, RectangleF) | Рисует указанное изображение. |
| virtual [EndDocument](../../aspose.html.rendering/device`2/enddocument)() |  |
| override [EndElement](../../aspose.html.rendering.xps/xpsdevice/endelement)(Element) | Завершает визуализацию элемента. |
| override [EndPage](../../aspose.html.rendering.xps/xpsdevice/endpage)() | Завершает визуализацию текущей страницы. |
| override [Fill](../../aspose.html.rendering.xps/xpsdevice/fill)(FillMode) | Заполняет всю область, ограниченную текущим путем. Если путь состоит из нескольких несвязанных подпутей, он заполняет внутренности всех подпутей, рассматриваемых вместе. Этот метод завершает текущий путь. |
| override [FillText](../../aspose.html.rendering.xps/xpsdevice/filltext)(string, PointF) | Заполняет указанную текстовую строку в указанном месте. |
| override [Flush](../../aspose.html.rendering.xps/xpsdevice/flush)() | Сбрасывает все данные в выходной поток. |
| override [LineTo](../../aspose.html.rendering.xps/xpsdevice/lineto)(PointF) | Добавляет отрезок прямой из текущей точки в точку (pt). Новая текущая точка - pt. |
| override [MoveTo](../../aspose.html.rendering.xps/xpsdevice/moveto)(PointF) | Начинает новый подконтур, перемещая текущую точку в координаты параметра pt, опуская любой соединительный отрезок. Если предыдущий метод построения пути в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; на пути не осталось следов предыдущей операции "MoveTo". |
| override [RestoreGraphicContext](../../aspose.html.rendering.xps/xpsdevice/restoregraphiccontext)() | Восстанавливает весь графический контекст до его прежнего значения, выталкивая его из стека. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device`2/savegraphiccontext)() |  |
| override [Stroke](../../aspose.html.rendering.xps/xpsdevice/stroke)() | Проводит линию по текущему пути. Заштрихованная линия следует за каждым прямым или изогнутым сегментом пути, с центром в сегменте со сторонами, параллельными ему. Каждый из подпутей пути обрабатывается отдельно. Этот метод завершает текущий путь. |
| override [StrokeAndFill](../../aspose.html.rendering.xps/xpsdevice/strokeandfill)(FillMode) | Штрихи и заливка текущего пути. Этот метод завершает текущий путь. |
| override [StrokeText](../../aspose.html.rendering.xps/xpsdevice/stroketext)(string, PointF) | Перемещает указанную текстовую строку в указанном месте. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext) | Содержит текущие параметры управления графикой для XpsDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы. |

### Смотрите также

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext)
* class [XpsRenderingOptions](../xpsrenderingoptions)
* пространство имен [Aspose.Html.Rendering.Xps](../../aspose.html.rendering.xps)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
