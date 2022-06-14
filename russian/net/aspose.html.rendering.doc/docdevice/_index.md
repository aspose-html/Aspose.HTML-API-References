---
title: DocDevice
second_title: Справочник по Aspose.HTML для .NET API
description: Представляет рендеринг в документ DOCX.
type: docs
weight: 4250
url: /ru/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Представляет рендеринг в документ DOCX.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DocDevice](docdevice#constructor)(ICreateStreamProvider) | Инициализирует новый экземпляр класса[`DocDevice`](../docdevice). |
| [DocDevice](docdevice#constructor_4)(Stream) | Инициализирует новый экземпляр класса[`DocDevice`](../docdevice)потоком вывода. |
| [DocDevice](docdevice#constructor_5)(string) | Инициализирует новый экземпляр класса[`DocDevice`](../docdevice)по имени выходного файла. |
| [DocDevice](docdevice#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Инициализирует новый экземпляр класса[`DocDevice`](../docdevice)с помощью параметров рендеринга и поставщика потока. |
| [DocDevice](docdevice#constructor_2)(DocRenderingOptions, Stream) | Инициализирует новый экземпляр класса[`DocDevice`](../docdevice)с помощью параметров рендеринга и выходного потока. |
| [DocDevice](docdevice#constructor_3)(DocRenderingOptions, string) | Инициализирует новый экземпляр класса[`DocDevice`](../docdevice)с параметрами рендеринга и именем выходного файла. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.html.rendering/device`2/options) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect)(RectangleF) | Добавляет прямоугольник к текущему пути как полный подпуть. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument)(Document) | Начинает визуализацию документа. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement)(Element, RectangleF) | Начинает рендеринг узла html. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage)(SizeF) | Начинает рендеринг новой страницы. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip)(FillMode) | Изменяет текущий путь отсечения, пересекая его с текущим путем, используя правило FillMode для определения области для заполнения. Этот метод завершает текущий путь. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath)() | Закрывает текущий подконтур, добавляя отрезок прямой линии от текущей точки до начальной точки подконтура. Если текущий подпуть уже закрыт, "ClosePath" ничего не делает. Этот оператор завершает текущий подпуть. При добавлении другого сегмента к текущему пути начинается новый подпуть, , даже если новый сегмент начинается в конечной точке, достигнутой методом ClosePath. |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая продолжается от текущей точки до точки pt2, с использованием pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка - pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage)(byte[], ImageType, RectangleF) | Рисует указанное изображение. |
| virtual [EndDocument](../../aspose.html.rendering/device`2/enddocument)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement)(Element) | Завершает визуализацию узла html. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage)() | Завершает визуализацию текущей страницы. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill)(FillMode) | Заполняет всю область, ограниченную текущим путем. Если путь состоит из нескольких несвязанных подпутей, он заполняет внутренности всех подпутей, рассматриваемых вместе. Этот метод завершает текущий путь. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext)(string, PointF) | Заполняет указанную текстовую строку в указанном месте. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush)() | Сбрасывает все данные в выходной поток. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto)(PointF) | Добавляет отрезок прямой из текущей точки в точку (pt). Новая текущая точка - pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto)(PointF) | Начинает новый подконтур, перемещая текущую точку в координаты параметра pt, опуская любой соединительный отрезок. Если предыдущий метод построения пути в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; на пути не осталось следов предыдущей операции "MoveTo". |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext)() | Восстанавливает весь графический контекст до его прежнего значения, выталкивая его из стека. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext)() | Помещает в стек копию всего графического контекста. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke)() | Проводит линию по текущему пути. Заштрихованная линия следует за каждым прямым или изогнутым сегментом пути, с центром в сегменте со сторонами, параллельными ему. Каждый из подпутей пути обрабатывается отдельно. Этот метод завершает текущий путь. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill)(FillMode) | Штрихи и заливка текущего пути. Этот метод завершает текущий путь. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext)(string, PointF) | Перемещает указанную текстовую строку в указанном месте. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext) | Содержит текущие параметры управления графикой для DocDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы. |

### Смотрите также

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2)
* class [DocGraphicContext](../docdevice.docgraphiccontext)
* class [DocRenderingOptions](../docrenderingoptions)
* пространство имен [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
