---
title: "Интерфейс IDevice"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.rendering.IDevice. Определяет методы и свойства, поддерживающие пользовательскую отрисовку графических элементов, таких как пути, текст и изображения."
type: docs

url: /ru/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Определяет методы и свойства, поддерживающие пользовательский рендеринг графических элементов, таких как пути, текст и изображения.

```java
public interface IDevice : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Получает графический контекст. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Получает параметры отрисовки. |

## Методы

| Имя | Описание |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Добавляет прямоугольник к текущему пути как завершённый подпуть. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Начинает рендеринг документа. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Начинает отрисовку элемента. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Начинает рендеринг новой страницы. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Изменяет текущий путь отсечения, пересекает его с текущим путем, используя FillRule для определения области заполнения. Этот метод завершает текущий путь. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Закрывает текущий подпуть, добавляя прямой отрезок от текущей точки к начальной точке подпути. Если текущий подпуть уже закрыт, "ClosePath" ничего не делает. Этот оператор завершает текущий подпуть. Добавление другого отрезка к текущему пути начинает новый подпуть, даже если новый отрезок начинается в конечной точке, достигнутой методом "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая проходит от текущей точки к точке pt3, используя pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка — pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Рисует указанное изображение. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Завершает отрисовку документа. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Завершает отрисовку элемента. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Завершает рендеринг текущей страницы. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Заполняет всю область, ограниченную текущим контуром. Если контур состоит из нескольких несвязанных подпутей, он заполняет внутренние части всех подпутей совместно. Этот метод завершает текущий контур. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Заполняет указанный текст String в указанном месте. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Сбрасывает все данные в выходной поток. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Добавляет прямой отрезок от текущей точки к точке (pt). Новая текущая точка — pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Начинает новую подпуть, перемещая текущую точку к координатам параметра pt, без создания соединительного отрезка. Если предыдущий метод построения контура в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; никаких следов предыдущей операции "MoveTo" в контуре не остаётся. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Восстанавливает весь графический контекст до его прежнего значения, извлекая его из стека. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Помещает копию всего графического контекста в стек. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Обводит линию вдоль текущего контура. Обводимая линия следует каждому прямому или изогнутому сегменту контура, центрируясь на сегменте со сторонами, параллельными ему. Каждая подпуть контура обрабатывается отдельно. Этот метод завершает текущий контур. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Обводит и заполняет текущий контур. Этот метод завершает текущий контур. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Обводит указанный текст String в указанном месте. |

### См. также

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
