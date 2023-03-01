---
title: Interface ICanvasPathMethods
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods интерфейс. Интерфейс ICanvasPathMethods используется для управления путями объектов.
type: docs
weight: 240
url: /ru/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Интерфейс ICanvasPathMethods используется для управления путями объектов.

```csharp
public interface ICanvasPathMethods
```

## Методы

| Имя | Описание |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Добавляет дугу к пути с центром в позиции (x, y) с радиусом r, начинающимся в startAngle и заканчивающимся в endAngle и идущим в заданном направлении против часовой стрелки (по умолчанию по часовой стрелке). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Добавляет дугу к пути с центром в позиции (x, y) с радиусом r, начинающимся в startAngle и заканчивающимся в endAngle и идущим в заданном направлении против часовой стрелки (по умолчанию по часовой стрелке). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Добавляет к пути дугу с заданными контрольными точками и радиусом, соединенную с предыдущей точкой прямой линией. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Добавляет кубическую кривую Безье к пути. Требует три балла. Первые две точки — контрольные, а третья — конечная. Начальная точка — это последняя точка текущего пути, которую можно изменить с помощью функции moveTo() перед созданием кривой Безье. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Заставляет точку пера вернуться к началу текущего подпути. Пытается провести прямую линию от текущей точки до начала. Если фигура уже закрыта или имеет только одну точку, эта функция ничего не делает. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Добавляет эллипс к пути с центром в позиции (x, y) с радиусами радиуса X и радиуса Y, начинающимися в startAngle и заканчивающимися в endAngle, идущими в заданном направлении против часовой стрелки (по умолчанию по часовой стрелке). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Добавляет эллипс к пути с центром в позиции (x, y) с радиусами радиуса X и радиуса Y, начинающимися в startAngle и заканчивающимися в endAngle, идущими в заданном направлении против часовой стрелки (по умолчанию по часовой стрелке). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Соединяет последнюю точку подпути с координатами x, y прямой линией. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Перемещает начальную точку нового подпути в координаты (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Добавляет квадратичную кривую Безье к текущему пути. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Создает путь для прямоугольника в позиции (x, y) с размером, определяемым шириной и высотой. |

### Смотрите также

* пространство имен [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* сборка [Aspose.HTML](../../)


