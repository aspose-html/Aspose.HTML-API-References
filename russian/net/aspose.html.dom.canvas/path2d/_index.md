---
title: Class Path2D
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Canvas.Path2D сорт. Интерфейс Path2D Canvas 2D API используется для объявления путей которые затем используются в объектах CanvasRenderingContext2D. Методы пути интерфейса CanvasRenderingContext2D также присутствуют в этом интерфейсе и позволяют вам создавать пути  которые вы можете сохранить и воспроизвести по мере необходимости на холсте.
type: docs
weight: 290
url: /ru/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Интерфейс Path2D Canvas 2D API используется для объявления путей, которые затем используются в объектах CanvasRenderingContext2D. Методы пути интерфейса CanvasRenderingContext2D также присутствуют в этом интерфейсе и позволяют вам создавать пути , которые вы можете сохранить и воспроизвести по мере необходимости на холсте.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Path2D](path2d/#constructor)() | возвращает вновь созданный объект Path2D object |
| [Path2D](path2d/#constructor_1)(Path2D) | возвращает вновь созданный экземпляр объекта Path2D с другим путем в качестве аргумента (создает копию) |
| [Path2D](path2d/#constructor_2)(string) | возвращает вновь созданный объект Path2D со строкой, состоящей из данных пути SVG. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Добавляет к пути путь, заданный аргументом. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Добавляет к пути путь, заданный аргументом. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Добавляет дугу к пути с центром в позиции (x, y) с радиусом r, начинающимся в startAngle и заканчивающимся в endAngle и идущим в заданном направлении против часовой стрелки (по умолчанию по часовой стрелке). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Добавляет дугу к пути с центром в позиции (x, y) с радиусом r, начинающимся в startAngle и заканчивающимся в endAngle и идущим в заданном направлении против часовой стрелки (по умолчанию по часовой стрелке). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Добавляет к пути дугу с заданными контрольными точками и радиусом, соединенную с предыдущей точкой прямой линией. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Добавляет кубическую кривую Безье к пути. Требует три балла. Первые две точки — контрольные, а третья — конечная. Начальная точка — это последняя точка текущего пути, которую можно изменить с помощью функции moveTo() перед созданием кривой Безье. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | Заставляет точку пера вернуться к началу текущего подпути. Пытается провести прямую линию от текущей точки до начала. Если фигура уже закрыта или имеет только одну точку, эта функция ничего не делает. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | Удаляет объект. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Добавляет эллипс к пути с центром в позиции (x, y) с радиусами радиуса X и радиуса Y, начинающимися в startAngle и заканчивающимися в endAngle, идущими в заданном направлении против часовой стрелки (по умолчанию по часовой стрелке). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Добавляет эллипс к пути с центром в позиции (x, y) с радиусами радиуса X и радиуса Y, начинающимися в startAngle и заканчивающимися в endAngle, идущими в заданном направлении против часовой стрелки (по умолчанию по часовой стрелке). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | Соединяет последнюю точку подпути с координатами x, y прямой линией. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | Перемещает начальную точку нового подпути в координаты (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Добавляет квадратичную кривую Безье к текущему пути. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Создает путь для прямоугольника в позиции (x, y) с размером, определяемым шириной и высотой. |

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* пространство имен [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* сборка [Aspose.HTML](../../)


