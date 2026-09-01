---
title: "SVGPathSeg Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg класс. Интерфейс SVGPathSeg является базовым интерфейсом, который соответствует отдельной команде в спецификации данных пути."
type: docs

url: /ru/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

Интерфейс SVGPathSeg является базовым интерфейсом, соответствующим отдельной команде в спецификации данных пути.

```java
public abstract class SVGPathSeg : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) Тип сегмента пути, указанный одной из констант, определённых в этом интерфейсе. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) Тип сегмента пути, указанный соответствующим односимвольным именем команды. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |

## Поля

| Имя | Описание |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Соответствует команде "абсолютный arcto" (A) в данных пути. |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Соответствует команде "относительный arcto" (a) в данных пути. |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Соответствует команде "closepath" (z) в данных пути. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Соответствует команде "абсолютный кубический Bézier curveto" (C) в данных пути. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Соответствует команде "относительный кубический Bézier curveto" (c) в данных пути. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Соответствует команде "абсолютный плавный кубический curveto" (S) в данных пути. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Соответствует команде "относительный плавный кубический curveto" (s) в данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Соответствует команде "абсолютный квадратичный Bézier curveto" (Q) в данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Соответствует команде "относительный квадратичный Bézier curveto" (q) в данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Соответствует команде "абсолютный плавный квадратичный curveto" (T) в данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Соответствует "relative smooth quadratic curveto" (t) команде данных пути. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Соответствует "absolute lineto" (L) команде данных пути. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Соответствует "absolute horizontal lineto" (H) команде данных пути. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Соответствует "relative horizontal lineto" (h) команде данных пути. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Соответствует "relative lineto" (l) команде данных пути. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Соответствует "absolute vertical lineto" (V) команде данных пути. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Соответствует "relative vertical lineto" (v) команде данных пути. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Соответствует "absolute moveto" (M) команде данных пути. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Соответствует "relative moveto" (m) команде данных пути. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Тип единицы не является одним из предопределённых типов. Недопустимо пытаться определить новое значение этого типа или пытаться переключить существующее значение на этот тип. |

### См. также

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
