---
title: "Класс SVGMatrix"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.svg.datatypes.SVGMatrix. Многие графические операции SVG используют 2x3 матрицы формы a c e b d f, которые при расширении до 3x3 матрицы для целей матричной арифметики становятся a c e b d f 0 0 1"
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Во многих графических операциях SVG используются 2×3 матрицы вида: [a c e] [b d f], которые при расширении до 3×3 матрицы для целей матричной арифметики становятся: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | Компонент A матрицы. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | Компонент B матрицы. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | Компонент C матрицы. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | Компонент D матрицы. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | Компонент E матрицы. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | Компонент F матрицы. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Выполняет умножение матриц. Эта матрица постмножается на другую матрицу, возвращая полученную новую матрицу. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Постмножает вращающее преобразование к текущей матрице и возвращает полученную матрицу. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Постмножает равномерное масштабирование к текущей матрице и возвращает полученную матрицу. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Постмножает неравномерное масштабирование к текущей матрице и возвращает полученную матрицу. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Постмультиплицирует трансформацию skewX к текущей матрице и возвращает результирующую матрицу. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Постмультиплицирует трансформацию skewY к текущей матрице и возвращает результирующую матрицу. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Возвращает строку, представляющую этот экземпляр. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Постмультиплицирует трансформацию перемещения к текущей матрице и возвращает результирующую матрицу. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
