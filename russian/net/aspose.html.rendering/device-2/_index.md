---
title: DeviceTGraphicContextTRenderingOptions
second_title: Справочник по Aspose.HTML для .NET API
description: Представляет базовый класс для реализации конкретных устройств рендеринга.
type: docs
weight: 4220
url: /ru/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Представляет базовый класс для реализации конкретных устройств рендеринга.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Параметр | Описание |
| --- | --- |
| TGraphicContext | Графический контекст, содержащий текущие параметры управления графикой |
| TRenderingOptions | Параметры рендеринга |

## Характеристики

| Имя | Описание |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } | Получает графический контекст |
| [Options](../../aspose.html.rendering/device`2/options) { get; } | Получает параметры рендеринга. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device`2/addrect)(RectangleF) | Добавляет прямоугольник к текущему пути как полный подпуть. |
| virtual [BeginDocument](../../aspose.html.rendering/device`2/begindocument)(Document) | Начинает визуализацию документа. |
| abstract [BeginElement](../../aspose.html.rendering/device`2/beginelement)(Element, RectangleF) | Начинает визуализацию узла. |
| virtual [BeginPage](../../aspose.html.rendering/device`2/beginpage)(SizeF) | Начинает рендеринг новой страницы. |
| abstract [Clip](../../aspose.html.rendering/device`2/clip)(FillMode) | Изменяет текущий путь отсечения, пересекая его с текущим путем, используя правило FillMode для определения области для заполнения. Этот метод завершает текущий путь. |
| abstract [ClosePath](../../aspose.html.rendering/device`2/closepath)() | Закрывает текущий подконтур, добавляя отрезок прямой линии от текущей точки до начальной точки подконтура. Если текущий подпуть уже закрыт, "ClosePath" ничего не делает. Этот оператор завершает текущий подпуть. При добавлении другого сегмента к текущему пути начинается новый подпуть, , даже если новый сегмент начинается в конечной точке, достигнутой методом ClosePath. |
| abstract [CubicBezierTo](../../aspose.html.rendering/device`2/cubicbezierto)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая продолжается от текущей точки до точки pt2, с использованием pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка - pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, освобождением или сбросом неуправляемых ресурсов. |
| abstract [DrawImage](../../aspose.html.rendering/device`2/drawimage)(byte[], ImageType, RectangleF) | Рисует указанное изображение. |
| virtual [EndDocument](../../aspose.html.rendering/device`2/enddocument)() | Завершает визуализацию документа. |
| abstract [EndElement](../../aspose.html.rendering/device`2/endelement)(Element) | Завершает визуализацию узла. |
| virtual [EndPage](../../aspose.html.rendering/device`2/endpage)() | Завершает визуализацию текущей страницы. |
| abstract [Fill](../../aspose.html.rendering/device`2/fill)(FillMode) | Заполняет всю область, ограниченную текущим путем. Если путь состоит из нескольких несвязанных подпутей, он заполняет внутренности всех подпутей, рассматриваемых вместе. Этот метод завершает текущий путь. |
| abstract [FillText](../../aspose.html.rendering/device`2/filltext)(string, PointF) | Заполняет указанную текстовую строку в указанном месте. |
| virtual [Flush](../../aspose.html.rendering/device`2/flush)() | Сбрасывает все данные в выходной поток. |
| abstract [LineTo](../../aspose.html.rendering/device`2/lineto)(PointF) | Добавляет отрезок прямой из текущей точки в точку (pt). Новая текущая точка - pt. |
| abstract [MoveTo](../../aspose.html.rendering/device`2/moveto)(PointF) | Начинает новый подконтур, перемещая текущую точку в координаты параметра pt, опуская любой соединительный отрезок. Если предыдущий метод построения пути в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; на пути не осталось следов предыдущей операции "MoveTo". |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device`2/restoregraphiccontext)() | Восстанавливает весь графический контекст до его прежнего значения, выталкивая его из стека. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device`2/savegraphiccontext)() | Помещает в стек копию всего графического контекста. |
| abstract [Stroke](../../aspose.html.rendering/device`2/stroke)() | Проводит линию по текущему пути. Заштрихованная линия следует за каждым прямым или изогнутым сегментом пути, с центром в сегменте со сторонами, параллельными ему. Каждый из подпутей пути обрабатывается отдельно. Этот метод завершает текущий путь. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device`2/strokeandfill)(FillMode) | Штрихи и заливка текущего пути. Этот метод завершает текущий путь. |
| abstract [StrokeText](../../aspose.html.rendering/device`2/stroketext)(string, PointF) | Перемещает указанную текстовую строку в указанном месте. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2) | Представляет объект конфигурации для устройств. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2) | Задает типы стратегий записи страниц в выходной поток\потоки. |

### Смотрите также

* interface [IDevice](../idevice)
* class [GraphicContext](../graphiccontext)
* class [RenderingOptions](../renderingoptions)
* пространство имен [Aspose.Html.Rendering](../../aspose.html.rendering)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
