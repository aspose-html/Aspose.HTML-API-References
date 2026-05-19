---
title: "SVGPathSeg Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg класс. Интерфейс SVGPathSeg является базовым интерфейсом, который соответствует отдельной команде в спецификации данных пути."
type: docs

url: /ru/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

Интерфейс SVGPathSeg — базовый интерфейс, соответствующий отдельной команде в спецификации данных пути.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) Тип сегмента пути, указанный одной из констант, определённых в этом интерфейсе. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Тип сегмента пути, указанный соответствующим односимвольным названием команды. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |

## Поля

| Имя | Описание |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Соответствует абсолютной команде "arcto" (A) в данных пути. |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Соответствует относительной команде "arcto" (a) в данных пути. |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Соответствует команде "closepath" (z) в данных пути. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Соответствует абсолютной кубической команде Bézier curveto (C) в данных пути. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Соответствует относительной кубической команде Bézier curveto (c) в данных пути. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Соответствует абсолютной плавной кубической команде curveto (S) в данных пути. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Соответствует относительной плавной кубической команде curveto (s) в данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Соответствует абсолютной квадратичной команде Bézier curveto (Q) в данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Соответствует относительной квадратичной команде Bézier curveto (q) в данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Соответствует абсолютной плавной квадратичной команде curveto (T) в данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Соответствует команде данных пути "relative smooth quadratic curveto" (t). |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Соответствует команде данных пути "absolute lineto" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Соответствует команде данных пути "absolute horizontal lineto" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Соответствует команде данных пути "relative horizontal lineto" (h). |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Соответствует команде данных пути "relative lineto" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Соответствует команде данных пути "absolute vertical lineto" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Соответствует команде данных пути "relative vertical lineto" (v). |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Соответствует команде данных пути "absolute moveto" (M). |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Соответствует команде данных пути "relative moveto" (m). |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Тип единицы не является одним из предопределённых типов. Недопустимо пытаться определить новое значение этого типа или пытаться переключить существующее значение на этот тип. |

### См. также

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
