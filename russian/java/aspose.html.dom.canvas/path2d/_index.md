---
title: "Класс Path2D"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.canvas.Path2D class. Интерфейс Path2D API Canvas 2D используется для объявления путей, которые затем применяются к объектам CanvasRenderingContext2D. Методы работы с путями интерфейса CanvasRenderingContext2D также присутствуют в этом интерфейсе и позволяют создавать пути, которые можно сохранять и воспроизводить по мере необходимости на холсте."
type: docs

url: /ru/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Интерфейс Path2D API Canvas 2D используется для объявления путей, которые затем применяются к объектам CanvasRenderingContext2D. Методы работы с путями интерфейса CanvasRenderingContext2D также присутствуют в этом интерфейсе и позволяют создавать пути, которые можно сохранять и воспроизводить по мере необходимости на холсте.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Path2D](path2d/#constructor)() | возвращает вновь созданный объект Path2D |
| [Path2D](path2d/#constructor_1)(Path2D) | возвращает вновь созданный объект Path2D с другим путем в качестве аргумента (создаёт копию) |
| [Path2D](path2d/#constructor_2)(String) | возвращает вновь созданный объект Path2D со строкой, содержащей данные SVG пути. |

## Методы

| Имя | Описание |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Добавляет к пути путь, переданный в аргументе. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Добавляет к пути путь, переданный в аргументе. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Добавляет дугу к пути, центрированной в позиции (x, y) с радиусом r, начиная с угла startAngle и заканчивая углом endAngle, движущуюся в заданном направлении против часовой стрелки (по умолчанию по часовой). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Добавляет дугу к пути, центрированной в позиции (x, y) с радиусом r, начиная с угла startAngle и заканчивая углом endAngle, движущуюся в заданном направлении против часовой стрелки (по умолчанию по часовой). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Добавляет дугу к пути с заданными контрольными точками и радиусом, соединённую с предыдущей точкой прямой линией. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Добавляет кубическую кривую Безье к пути. Требуются три точки. Первые две точки являются контрольными, а третья — конечной точкой. Начальная точка — последняя точка текущего пути, которую можно изменить с помощью moveTo() перед созданием кривой Безье. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Заставляет точку пера вернуться к началу текущего подпути. Пытается нарисовать прямую линию от текущей точки к началу. Если фигура уже закрыта или содержит только одну точку, эта функция ничего не делает. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Освобождает объект. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Добавляет эллипс к пути, центрированный в позиции (x, y) с радиусами radiusX и radiusY, начиная с угла startAngle и заканчивая углом endAngle, движущийся в заданном направлении против часовой стрелки (по умолчанию по часовой). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Добавляет эллипс к пути, центрированный в позиции (x, y) с радиусами radiusX и radiusY, начиная с угла startAngle и заканчивая углом endAngle, движущийся в заданном направлении против часовой стрелки (по умолчанию по часовой). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Соединяет последнюю точку подпути с координатами x, y прямой линией. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Перемещает начальную точку нового подпути к координатам (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Добавляет квадратичную кривую Безье к текущему пути. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Создаёт путь для прямоугольника в позиции (x, y) с размерами, определяемыми шириной width и высотой height. |

### См. также

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
