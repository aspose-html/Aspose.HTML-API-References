---
title: Interface IDevice
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Rendering.IDevice интерфейс. Определяет методы и свойства поддерживающие пользовательскую визуализацию графических элементов таких как контуры текст и изображения.
type: docs
weight: 4280
url: /ru/net/aspose.html.rendering/idevice/
---
## IDevice interface

Определяет методы и свойства, поддерживающие пользовательскую визуализацию графических элементов, таких как контуры, текст и изображения.

```csharp
public interface IDevice : IDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | Получает графический контекст. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | Получает параметры рендеринга. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | Добавляет прямоугольник к текущему пути в качестве полного подпути. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | Начинает визуализацию документа. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Начинает визуализацию элемента. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | Начинает рендеринг новой страницы. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | Изменяет текущий путь отсечения, пересекая его с текущим путем, используя правило FillMode для определения области для заполнения. Этот метод завершает текущий путь. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | Закрывает текущий подконтур, добавляя отрезок прямой линии от текущей точки до начальной точки подконтура. Если текущий подпуть уже закрыт, "ClosePath" ничего не делает. Этот оператор завершает текущий подпуть. При добавлении другого сегмента к текущему пути начинается новый подпуть, , даже если новый сегмент начинается в конечной точке, достигнутой методом ClosePath. |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая продолжается от текущей точки до точки pt3, , используя pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка - pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | Рисует указанное изображение. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | Завершает визуализацию документа. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | Завершает визуализацию элемента. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | Завершает визуализацию текущей страницы. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | Заполняет всю область, ограниченную текущим путем. Если путь состоит из нескольких несвязанных подпутей, он заполняет внутренности всех подпутей, рассматриваемых вместе. Этот метод завершает текущий путь. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | Заполняет указанную текстовую строку в указанном месте. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | Сбрасывает все данные в выходной поток. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | Добавляет отрезок прямой от текущей точки до точки (pt). Новая текущая точка - pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | Начинает новый подпуть, перемещая текущую точку в координаты параметра pt, опуская любой соединительный отрезок. Если предыдущий метод построения пути в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; в пути не осталось следов предыдущей операции "MoveTo". |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | Восстанавливает весь графический контекст до его прежнего значения, извлекая его из стека. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | Помещает копию всего графического контекста в стек. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | Проводит линию по текущему пути. Заштрихованная линия следует за каждым прямым или изогнутым сегментом пути, центрируется на сегменте со сторонами, параллельными ему. Каждый из подпутей пути обрабатывается отдельно. Этот метод завершает текущий путь. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | Штрихует и заполняет текущий путь. Этот метод завершает текущий путь. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | Перемещает указанную текстовую строку в указанном месте. |

### Смотрите также

* пространство имен [Aspose.Html.Rendering](../../aspose.html.rendering/)
* сборка [Aspose.HTML](../../)


