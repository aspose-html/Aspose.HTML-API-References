---
title: ImageDevice
second_title: Справочник по Aspose.HTML для .NET API
description: Представляет рендеринг в растровые форматыjpeg png bmp gif tiff.
type: docs
weight: 4380
url: /ru/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Представляет рендеринг в растровые форматы:jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageDevice](imagedevice#constructor)(ICreateStreamProvider) | Инициализирует новый экземпляр класса[`ImageDevice`](../imagedevice). |
| [ImageDevice](imagedevice#constructor_4)(Stream) | Инициализирует новый экземпляр класса[`ImageDevice`](../imagedevice). |
| [ImageDevice](imagedevice#constructor_5)(string) | Инициализирует новый экземпляр класса[`ImageDevice`](../imagedevice). |
| [ImageDevice](imagedevice#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Инициализирует новый экземпляр класса[`ImageDevice`](../imagedevice)с помощью параметров рендеринга и поставщика потоков. |
| [ImageDevice](imagedevice#constructor_2)(ImageRenderingOptions, Stream) | Инициализирует новый экземпляр класса[`ImageDevice`](../imagedevice)с помощью параметров рендеринга и выходного потока. |
| [ImageDevice](imagedevice#constructor_3)(ImageRenderingOptions, string) | Инициализирует новый экземпляр класса[`ImageDevice`](../imagedevice)параметрами рендеринга и именем выходного файла. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics) { get; } | Получает экземпляр Graphics. |
| [Options](../../aspose.html.rendering/device`2/options) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect)(RectangleF) | Добавляет прямоугольник к текущему пути как полный подпуть. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument)(Document) | Начинает визуализацию документа. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement)(Element, RectangleF) | Начинает визуализацию элемента. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage)(SizeF) | Начинает рендеринг новой страницы. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip)(FillMode) | Изменяет текущий путь отсечения, пересекая его с текущим путем, используя правило FillMode для определения области для заполнения. Этот метод завершает текущий путь. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath)() | Закрывает текущий подконтур, добавляя отрезок прямой линии от текущей точки до начальной точки подконтура. Если текущий подпуть уже закрыт, "ClosePath" ничего не делает. Этот оператор завершает текущий подпуть. При добавлении другого сегмента к текущему пути начинается новый подпуть, , даже если новый сегмент начинается в конечной точке, достигнутой методом ClosePath. |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая продолжается от текущей точки до точки pt2, с использованием pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка - pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage)(byte[], ImageType, RectangleF) | Рисует указанное изображение. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument)() | Завершает визуализацию документа. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement)(Element) | Завершает визуализацию элемента. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage)() | Завершает визуализацию текущей страницы. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill)(FillMode) | Заполняет всю область, ограниченную текущим путем. Если путь состоит из нескольких несвязанных подпутей, он заполняет внутренности всех подпутей, рассматриваемых вместе. Этот метод завершает текущий путь. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext)(string, PointF) | Заполняет указанную текстовую строку в указанном месте. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush)() | Сбрасывает все данные в выходной поток. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto)(PointF) | Добавляет отрезок прямой из текущей точки в точку (pt). Новая текущая точка - pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto)(PointF) | Начинает новый подконтур, перемещая текущую точку в координаты параметра pt, опуская любой соединительный отрезок. Если предыдущий метод построения пути в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; на пути не осталось следов предыдущей операции "MoveTo". |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext)() | Восстанавливает весь графический контекст до его прежнего значения, выталкивая его из стека. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext)() | Помещает в стек копию всего графического контекста. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke)() | Проводит линию по текущему пути. Заштрихованная линия следует за каждым прямым или изогнутым сегментом пути, с центром в сегменте со сторонами, параллельными ему. Каждый из подпутей пути обрабатывается отдельно. Этот метод завершает текущий путь. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill)(FillMode) | Штрихи и заливка текущего пути. Этот метод завершает текущий путь. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext)(string, PointF) | Перемещает указанную текстовую строку в указанном месте. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext) | Содержит текущие параметры управления графикой для[`ImageDevice`](../imagedevice). Эти параметры определяют глобальную структуру, в которой выполняются графические операторы. |

### Смотрите также

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2)
* class [ImageRenderingOptions](../imagerenderingoptions)
* пространство имен [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
