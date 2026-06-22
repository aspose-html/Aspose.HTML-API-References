---
title: "Класс DeviceTGraphicContextTRenderingOptions"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions. Представляет базовый класс для реализации конкретных устройств рендеринга."
type: docs

url: /ru/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Представляет базовый класс для реализации конкретных устройств рендеринга.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Параметр | Описание |
| --- | --- |
| TGraphicContext | Графический контекст, содержащий текущие параметры управления графикой |
| TRenderingOptions | Параметры рендеринга |

## Свойства

| Имя | Описание |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Получает графический контекст |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Получает параметры рендеринга. |

## Методы

| Имя | Описание |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Добавляет прямоугольник к текущему пути как завершённый подпуть. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Начинает рендеринг документа. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Начинает рендеринг узла. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Начинает рендеринг новой страницы. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Изменяет текущий путь отсечения, пересекает его с текущим путем, используя FillRule для определения области заполнения. Этот метод завершает текущий путь. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Замыкает текущий подпуть, добавляя прямой отрезок от текущей точки к начальной точке подпути. Если текущий подпуть уже закрыт, \"ClosePath\" ничего не делает. Этот оператор завершает текущий подпуть. Добавление другого отрезка к текущему пути начинает новый подпуть, даже если новый отрезок начинается в конечной точке, достигнутой методом \"ClosePath\". |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая проходит от текущей точки к точке pt2, используя pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка — pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Рисует указанное изображение. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Завершает отрисовку документа. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Завершает рендеринг узла. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Завершает рендеринг текущей страницы. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Заполняет всю область, ограниченную текущим контуром. Если контур состоит из нескольких несвязанных подпутей, он заполняет внутренние части всех подпутей вместе. Этот метод завершает текущий контур. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Заполняет указанную строку String в указанном месте. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Сбрасывает все данные в поток вывода. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Добавляет прямой отрезок от текущей точки к точке (pt). Новая текущая точка — pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Начинает новую подпуть, перемещая текущую точку к координатам параметра pt, без соединительного отрезка. Если предыдущий метод построения контура в текущем контуре также был "MoveTo", новый "MoveTo" переопределяет его; никаких следов предыдущей операции "MoveTo" в контуре не остаётся. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Восстанавливает весь графический контекст до его прежнего значения, извлекая его из стека. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Помещает копию всего графического контекста в стек. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Рисует линию вдоль текущего контура. Нарисованная линия следует каждому прямому или изогнутому сегменту контура, центрирована на сегменте со сторонами, параллельными ему. Каждая подпуть контура обрабатывается отдельно. Этот метод завершает текущий контур. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Рисует и заполняет текущий контур. Этот метод завершает текущий контур. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Рисует указанную строку String в указанном месте. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Указывает типы стратегий записи страниц в выходные потоки. |

### См. также

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
