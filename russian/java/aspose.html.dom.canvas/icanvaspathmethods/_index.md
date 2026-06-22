---
title: "Интерфейс ICanvasPathMethods"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods interface. Интерфейс ICanvasPathMethods используется для манипулирования путями объектов."
type: docs

url: /ru/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Интерфейс ICanvasPathMethods используется для манипулирования путями объектов.

```java
public interface ICanvasPathMethods
```

## Методы

| Имя | Описание |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Добавляет дугу к пути, центрированной в позиции (x, y) с радиусом r, начиная с угла startAngle и заканчивая углом endAngle, движущуюся в указанном направлении против часовой стрелки (по умолчанию по часовой). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Добавляет дугу к пути, центрированной в позиции (x, y) с радиусом r, начиная с угла startAngle и заканчивая углом endAngle, движущуюся в указанном направлении против часовой стрелки (по умолчанию по часовой). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Добавляет дугу к пути с заданными контрольными точками и радиусом, соединённую с предыдущей точкой прямой линией. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Добавляет кубическую кривую Безье к пути. Требуются три точки. Первые две точки являются контрольными точками, а третья — конечной точкой. Начальная точка — это последняя точка текущего пути, которую можно изменить с помощью moveTo() перед созданием кривой Безье. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Заставляет точку пера вернуться к началу текущего подпути. Пытается нарисовать прямую линию от текущей точки к началу. Если фигура уже закрыта или содержит только одну точку, эта функция ничего не делает. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Добавляет эллипс к пути, центрированный в позиции (x, y) с радиусами radiusX и radiusY, начиная с угла startAngle и заканчивая углом endAngle, движущийся в указанном направлении против часовой стрелки (по умолчанию по часовой). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Добавляет эллипс к пути, центрированный в позиции (x, y) с радиусами radiusX и radiusY, начиная с угла startAngle и заканчивая углом endAngle, движущийся в указанном направлении против часовой стрелки (по умолчанию по часовой). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Соединяет последнюю точку подпути с координатами x, y прямой линией. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Перемещает начальную точку нового подпути к координатам (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Добавляет квадратичную кривую Безье к текущему пути. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Создаёт путь для прямоугольника в позиции (x, y) с размерами, определяемыми шириной width и высотой height. |

### См. также

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
