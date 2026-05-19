---
title: "Класс DocDevice"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.rendering.doc.DocDevice class. Представляет рендеринг в документ DOCX"
type: docs

url: /ru/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Представляет рендеринг в документ DOCX.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Инициализирует новый экземпляр класса `DocDevice`. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Инициализирует новый экземпляр класса `DocDevice` с помощью выходного потока. |
| [DocDevice](docdevice/#constructor_5)(String) | Инициализирует новый экземпляр класса `DocDevice` по имени выходного файла. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Инициализирует новый экземпляр класса `DocDevice` с параметрами рендеринга и поставщиком потока. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Инициализирует новый экземпляр класса `DocDevice` с параметрами рендеринга и выходным потоком. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Инициализирует новый экземпляр класса `DocDevice` с параметрами рендеринга и именем выходного файла. |

## Свойства

| Имя | Описание |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Методы

| Имя | Описание |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Добавляет прямоугольник к текущему пути как завершённый подпуть. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Начинает рендеринг документа. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Начинает рендеринг HTML‑узла. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Начинает рендеринг новой страницы. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Изменяет текущий путь отсечения, пересекает его с текущим путём, используя правило FillMode для определения области заполнения. Этот метод завершает текущий путь. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Закрывает текущий подпуть, добавляя прямой отрезок от текущей точки к начальной точке подпути. Если текущий подпуть уже закрыт, "ClosePath" ничего не делает. Этот оператор завершает текущий подпуть. Добавление другого отрезка к текущему пути начинает новый подпуть, даже если новый отрезок начинается в конечной точке, достигнутой методом "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Добавляет кубическую кривую Безье к текущему пути. Кривая проходит от текущей точки к точке pt2, используя pt1 и pt2 в качестве контрольных точек Безье. Новая текущая точка — pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Рисует указанное изображение. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Завершает рендеринг HTML‑узла. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Завершает рендеринг текущей страницы. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Заполняет всю область, ограниченную текущим контуром. Если контур состоит из нескольких несвязанных подпутей, он заполняет внутренние части всех подпутей совместно. Этот метод завершает текущий контур. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Заполняет указанный текст String в указанном месте. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Сбрасывает все данные в выходной поток. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Добавляет прямой отрезок от текущей точки к точке (pt). Новая текущая точка — pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Начинает новую подпуть, перемещая текущую точку к координатам параметра pt, без создания соединительного отрезка. Если предыдущий метод построения контура в текущем пути также был "MoveTo", новый "MoveTo" переопределяет его; никаких следов предыдущей операции "MoveTo" в контуре не остаётся. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Обводит линию вдоль текущего контура. Обводимая линия следует каждому прямому или изогнутому сегменту контура, центрируясь на сегменте со сторонами, параллельными ему. Каждая подпуть контура обрабатывается отдельно. Этот метод завершает текущий контур. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Обводит и заполняет текущий контур. Этот метод завершает текущий контур. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Обводит указанный текст String в указанном месте. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Содержит текущие параметры управления графикой для DocDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы. |

### См. также

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
