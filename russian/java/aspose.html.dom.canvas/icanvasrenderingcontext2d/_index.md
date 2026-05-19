---
title: "Интерфейс ICanvasRenderingContext2D"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.canvas.ICanvasRenderingContext2D. Интерфейс ICanvasRenderingContext2D используется для рисования прямоугольников, текста, изображений и других объектов на элементе canvas. Он предоставляет 2‑D контекст рендеринга для поверхности рисования элемента canvas."
type: docs

url: /ru/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

Интерфейс ICanvasRenderingContext2D используется для рисования прямоугольников, текста, изображений и других объектов на элементе canvas. Он предоставляет 2‑D контекст рендеринга для поверхности рисования элемента canvas.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) Только для чтения обратная ссылка на HTMLCanvasElement. Может быть null, если не связан с элементом canvas. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Методы

| Имя | Описание |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Начинает новый путь, очищая список под‑путей. Вызовите этот метод, когда хотите создать новый путь. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Удаляет все области попадания с canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Устанавливает все пиксели в прямоугольнике, определённом начальной точкой (x, y) и размерами (width, height), в прозрачный чёрный цвет, стирая ранее нарисованное содержимое. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Создаёт новую область отсечения, вычисляя пересечение текущей области отсечения и области, описанной путем, используя правило ненулевого числа оборотов. Открытые под‑пути должны быть неявно закрыты при вычислении области отсечения, без изменения самих под‑путей. Новая область отсечения заменяет текущую. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Создаёт новую область отсечения, вычисляя пересечение текущей области отсечения и области, описанной путем, используя правило ненулевого числа оборотов. Открытые под‑пути должны быть неявно закрыты при вычислении области отсечения, без изменения самих под‑путей. Новая область отсечения заменяет текущую. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Создаёт новую область отсечения, вычисляя пересечение текущей области отсечения и области, описанной путем, используя правило ненулевого числа оборотов. Открытые под‑пути должны быть неявно закрыты при вычислении области отсечения, без изменения самих под‑путей. Новая область отсечения заменяет текущую. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Создаёт новый пустой объект ImageData с указанными размерами. Все пиксели нового объекта являются прозрачным чёрным. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Создаёт новый пустой объект ImageData с указанными размерами. Все пиксели нового объекта являются прозрачным чёрным. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Создаёт линейный градиент вдоль линии, заданной координатами, представленными параметрами. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Создаёт узор, используя указанное изображение (CanvasImageSource). Он повторяет источник в направлениях, заданных аргументом repetition. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Создаёт узор, используя указанное изображение (CanvasImageSource). Он повторяет источник в направлениях, заданных аргументом repetition. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Создаёт радиальный градиент, заданный координатами двух кругов, представленных параметрами. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Если данный элемент находится в фокусе, этот метод рисует кольцо фокуса вокруг текущего пути. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Рисует указанное изображение. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Рисует указанное изображение. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Рисует указанное изображение. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Рисует указанное изображение. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Рисует указанное изображение. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Рисует указанное изображение. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Заполняет подпути текущим стилем заливки и алгоритмом по умолчанию CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Заполняет подпути текущим стилем заливки. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Заполняет подпути текущим стилем заливки и алгоритмом по умолчанию CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Заполняет подпути текущим стилем заливки. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Рисует заполненный прямоугольник в позиции (x, y), размер которого определяется шириной и высотой. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Рисует (заполняет) заданный текст в указанной позиции (x,y). |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Рисует (заполняет) заданный текст в указанной позиции (x,y). |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Возвращает объект ImageData, представляющий исходные пиксельные данные области холста, обозначенной прямоугольником, начинающимся в (sx, sy) и имеющим ширину sw и высоту sh. Этот метод не зависит от матрицы преобразования холста. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Сообщает, содержится ли указанный пункт в текущем пути. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Сообщает, содержится ли указанный пункт в текущем пути. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Сообщает, содержится ли указанный пункт в текущем пути. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Сообщает, содержится ли указанный пункт в текущем пути. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Сообщает, находится ли указанный пункт внутри области, образованной обводкой пути. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Сообщает, находится ли указанный пункт внутри области, образованной обводкой пути. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Возвращает объект TextMetrics. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Наносит данные из заданного объекта ImageData на растровое изображение. Если указан «грязный» прямоугольник, рисуются только пиксели из этого прямоугольника. Этот метод не зависит от матрицы преобразования холста. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Наносит данные из заданного объекта ImageData на растровое изображение. Если указан «грязный» прямоугольник, рисуются только пиксели из этого прямоугольника. Этот метод не зависит от матрицы преобразования холста. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Удаляет область попадания с указанным идентификатором с холста. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Сбрасывает текущее преобразование к единичной матрице. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Восстанавливает состояние стиля рисования до последнего элемента в «стеке состояний», сохранённого функцией save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Добавляет вращение к матрице преобразования. Параметр angle представляет угол вращения по часовой стрелке и задаётся в радианах. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Сохраняет текущее состояние стиля рисования в стек, чтобы вы могли отменить любые изменения с помощью restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Добавляет масштабирование к единицам холста по x горизонтально и по y вертикально. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Сбрасывает текущее преобразование к единичной матрице, а затем вызывает метод transform() с теми же аргументами. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Обводит подпути текущим стилем обводки. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Обводит подпути текущим стилем обводки. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Рисует прямоугольник, начинающийся в точке (x, y) и имеющий ширину w и высоту h, на холсте, используя текущий стиль обводки. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Рисует (обводит) заданный текст в указанной позиции (x, y). |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Рисует (обводит) заданный текст в указанной позиции (x, y). |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Умножает текущую матрицу преобразования на матрицу, описанную её аргументами. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Добавляет трансляцию, перемещая холст и его начало координат x горизонтально и y вертикально по сетке. |

### См. также

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
