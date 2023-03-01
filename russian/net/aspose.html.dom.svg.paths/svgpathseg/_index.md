---
title: Class SVGPathSeg
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Svg.Paths.SVGPathSeg сорт. Интерфейс SVGPathSeg  это базовый интерфейс который соответствует одной команде в спецификации данных пути.
type: docs
weight: 1690
url: /ru/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

Интерфейс SVGPathSeg — это базовый интерфейс, который соответствует одной команде в спецификации данных пути.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) { get; } | Тип сегмента пути, указанный одной из констант, определенных на этом интерфейсе. |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | Тип сегмента пути, определяемый соответствующим односимвольным именем команды. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и (необязательно) управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |

## Поля

| Имя | Описание |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | Соответствует команде данных пути "absolute arcto" (A). |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | Соответствует "относительной arcto" (a) команде данных пути. |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | Соответствует команде данных пути closepath (z). |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | Соответствует команде данных пути "абсолютная кубическая кривая Безье" (C). |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | Соответствует "относительной кубической кривой Безье к" (c) команде данных пути. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | Соответствует команде данных пути "абсолютно гладкая кубическая кривая" (S). |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | Соответствует команде данных пути "относительная гладкая кубическая кривая к" (s). |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | Соответствует команде данных пути "абсолютная квадратичная кривая Безье" (Q). |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | Соответствует "относительной квадратичной кривой Безье к" (q) команде данных пути. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | Соответствует команде данных пути "абсолютно гладкая квадратичная кривая к" (T). |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | Соответствует команде данных пути "относительная гладкая квадратичная кривая к" (t). |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | Соответствует команде данных пути "absolute lineto" (L). |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | Соответствует команде данных пути "абсолютная горизонтальная линия до" (H). |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | Соответствует команде данных пути "относительная горизонтальная линия к" (h). |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | Соответствует команде данных пути "относительная линия к" (l). |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | Соответствует команде данных пути "абсолютная вертикальная линия к" (V). |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | Соответствует команде данных пути "относительная вертикальная линия к" (v). |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | Соответствует команде данных пути "абсолютный переход" (M). |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | Соответствует команде данных пути "относительного перемещения" (m). |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | Тип юнита не является одним из предопределенных типов. Недопустимо пытаться определить новое значение этого типа или пытаться переключить существующее значение на этот тип. |

### Смотрите также

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* пространство имен [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* сборка [Aspose.HTML](../../)


