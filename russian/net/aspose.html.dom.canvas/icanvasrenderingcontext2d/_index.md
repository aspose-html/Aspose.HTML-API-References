---
title: ICanvasRenderingContext2D
second_title: Справочник по Aspose.HTML для .NET API
description: Интерфейс ICanvasRenderingContext2D используется для рисования прямоугольников текста изображений и других объектов на элементе холста. Он обеспечивает контекст 2D-рендеринга для поверхности рисования элемента холста.
type: docs
weight: 370
url: /ru/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

Интерфейс ICanvasRenderingContext2D используется для рисования прямоугольников, текста, изображений и других объектов на элементе холста. Он обеспечивает контекст 2D-рендеринга для поверхности рисования элемента холста.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas) { get; } | Обратная ссылка только для чтения на HTMLCanvasElement. Может быть нулевым, если он не связан с элементом холста. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle) { get; set; } | Цвет или стиль для использования внутри фигур. По умолчанию:(черный). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha) { get; set; } | Альфа-значение, которое применяется к фигурам и изображениям до их компоновки на холсте. По умолчанию 1.0 (непрозрачный). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation) { get; set; } | При применении globalAlpha устанавливает, как фигуры и изображения рисуются на существующем растровом изображении. По умолчанию:(исходник) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled) { get; set; } | Режим сглаживания изображения; если отключено, изображения не будут сглаживаться при масштабировании. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur) { get; set; } | Определяет эффект размытия. По умолчанию 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor) { get; set; } | Цвет тени. По умолчанию полностью прозрачный черный. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx) { get; set; } | Расстояние по горизонтали, на которое будет смещена тень. По умолчанию 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety) { get; set; } | Расстояние по вертикали, на которое будет смещена тень. По умолчанию 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle) { get; set; } | Цвет или стиль линий вокруг фигур. По умолчанию:(черный). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion)(Dictionary&lt;string, string&gt;) | Добавляет область попадания на холст. Это позволяет упростить обнаружение попаданий, позволяет направлять события к элементам DOM, и позволяет пользователям исследовать холст, не видя его. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath)() | Начинает новый путь, очищая список подпутей. Вызовите этот метод, если хотите создать новый путь. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions)() | Удаляет все пораженные области с холста. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect)(double, double, double, double) | Устанавливает все пиксели в прямоугольнике, определяемом начальной точкой (x, y) и размером (шириной, высотой), в прозрачный черный цвет, стирая все ранее нарисованное содержимое. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip#clip)() | Создает новую область отсечения, вычисляя пересечение текущей области отсечения и области, описываемой путем, используя правило ненулевого числа витков. Открытые вложенные пути должны быть неявно закрыты при вычислении области отсечения, не затрагивая фактические вложенные пути. Новая область отсечения заменяет текущую область отсечения. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip#clip_1)(CanvasFillRule) | Создает новую область отсечения, вычисляя пересечение текущей области отсечения и области, описываемой путем, используя правило ненулевого числа витков. Открытые вложенные пути должны быть неявно закрыты при вычислении области отсечения, не затрагивая фактические вложенные пути. Новая область отсечения заменяет текущую область отсечения. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip#clip_2)(Path2D, CanvasFillRule) | Создает новую область отсечения, вычисляя пересечение текущей области отсечения и области, описываемой путем, используя правило ненулевого числа витков. Открытые вложенные пути должны быть неявно закрыты при вычислении области отсечения, не затрагивая фактические вложенные пути. Новая область отсечения заменяет текущую область отсечения. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata#createimagedata)(IImageData) | Создает новый пустой объект ImageData с указанными размерами. Все пиксели в новом объекте прозрачно-черные. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata#createimagedata_1)(double, double) | Создает новый пустой объект ImageData с указанными размерами. Все пиксели в новом объекте прозрачно-черные. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient)(double, double, double, double) | Создает линейный градиент вдоль линии, заданной координатами, представленными параметрами. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern#createpattern)(HTMLCanvasElement, string) | Создает шаблон, используя указанное изображение (CanvasImageSource). Повторяет источник в направлениях, указанных аргументом повторения. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern#createpattern_1)(HTMLImageElement, string) | Создает шаблон, используя указанное изображение (CanvasImageSource). Повторяет источник в направлениях, указанных аргументом повторения. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient)(double, double, double, double, double, double) | Создает радиальный градиент, заданный координатами двух кругов, представленных параметрами. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded)(Element) | Если данный элемент находится в фокусе, этот метод рисует кольцо фокуса вокруг текущего пути. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage)(HTMLCanvasElement, double, double) | Рисует указанное изображение. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_3)(HTMLImageElement, double, double) | Рисует указанное изображение. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Рисует указанное изображение. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_4)(HTMLImageElement, double, double, double, double) | Рисует указанное изображение. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Рисует указанное изображение. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Рисует указанное изображение. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill#fill)() | Заполняет подпути текущим стилем заливки и алгоритмом по умолчанию CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill#fill_1)(CanvasFillRule) | Заполняет подконтуры текущим стилем заливки. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill#fill_2)(Path2D) | Заполняет подпути текущим стилем заливки и алгоритмом по умолчанию CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill#fill_3)(Path2D, CanvasFillRule) | Заполняет подконтуры текущим стилем заливки. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect)(double, double, double, double) | Рисует закрашенный прямоугольник в позиции (x, y), размер которого определяется шириной и высотой. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext#filltext)(string, double, double) | Рисует (заполняет) заданный текст в заданной позиции (x,y). |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext#filltext_1)(string, double, double, double) | Рисует (заполняет) заданный текст в заданной позиции (x,y). |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata)(double, double, double, double) | Возвращает объект ImageData, представляющий базовые пиксельные данные для области холста, обозначенной прямоугольником, который начинается с (sx, sy) и имеет ширину sw и высоту sh . На этот метод не влияет матрица преобразования холста. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath#ispointinpath_2)(double, double) | Сообщает, содержится ли указанная точка в текущем пути. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath#ispointinpath_3)(double, double, CanvasFillRule) | Сообщает, содержится ли указанная точка в текущем пути. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath#ispointinpath)(Path2D, double, double) | Сообщает, содержится ли указанная точка в текущем пути. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Сообщает, содержится ли указанная точка в текущем пути. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke#ispointinstroke_1)(double, double) | Сообщает, находится ли указанная точка внутри области, содержащейся при обводке пути. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke#ispointinstroke)(Path2D, double, double) | Сообщает, находится ли указанная точка внутри области, содержащейся при обводке пути. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext)(string) | Возвращает объект TextMetrics. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata#putimagedata)(IImageData, double, double) | Рисует данные из данного объекта ImageData на растровое изображение. Если предоставлен грязный прямоугольник, закрашиваются только пиксели из этого прямоугольника. На этот метод не влияет матрица преобразования холста. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata#putimagedata_1)(IImageData, double, double, double, double, double, double) | Рисует данные из данного объекта ImageData на растровое изображение. Если предоставлен грязный прямоугольник, закрашиваются только пиксели из этого прямоугольника. На этот метод не влияет матрица преобразования холста. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion)(string) | Удаляет область попадания с указанным id с холста. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform)() | Сбрасывает текущее преобразование по единичной матрице. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore)() | Восстанавливает состояние стиля рисования до последнего элемента в 'стеке состояний', сохраненного с помощью save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate)(double) | Добавляет поворот к матрице преобразования. Аргумент угла представляет угол поворота по часовой стрелке и выражается в радианах. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save)() | Сохраняет текущее состояние стиля рисования с помощью стека, чтобы вы могли отменить любое изменение, внесенное в него, с помощью restore(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale)(double, double) | Добавляет преобразование масштабирования к единицам холста по x по горизонтали и по y по вертикали. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform)(double, double, double, double, double, double) | Сбрасывает текущее преобразование в единичную матрицу, а затем вызывает метод transform() с теми же аргументами. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke#stroke)() | Обводка подконтуров текущим стилем обводки. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke#stroke_1)(Path2D) | Обводка подконтуров текущим стилем обводки. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect)(double, double, double, double) | Рисует на холсте прямоугольник с начальной точкой (x, y), шириной aw и высотой h, используя текущий стиль штриха. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext#stroketext)(string, double, double) | Рисует (штрихует) заданный текст в заданной (x, y) позиции. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext#stroketext_1)(string, double, double, double?) | Рисует (штрихует) заданный текст в заданной (x, y) позиции. |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform)(double, double, double, double, double, double) | Умножает текущую матрицу преобразования на матрицу, описанную ее аргументами. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate)(double, double) | Добавляет трансформацию перемещения, перемещая холст и его начало координат x по горизонтали и y по вертикали на сетке. |

### Смотрите также

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles)
* interface [ICanvasPathMethods](../icanvaspathmethods)
* пространство имен [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
