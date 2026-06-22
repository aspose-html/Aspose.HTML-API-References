---
title: "Класс SVGTransform"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.svg.datatypes.SVGTransform. SVGTransform — это интерфейс одной из компонентных трансформаций внутри SVGTransformList, поэтому объект SVGTransform соответствует отдельному компоненту, например масштабированию или матрице в спецификации атрибута transform"
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform — это интерфейс одной из компонентных трансформаций внутри SVGTransformList; таким образом, объект SVGTransform соответствует отдельной компоненте (например, 'scale(…)' или 'matrix(…)') в спецификации атрибута ‘transform’.

```java
public class SVGTransform : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Удобный атрибут для SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY. Он хранит указанный угол. Для SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE и SVG_TRANSFORM_SCALE угол будет равен нулю. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) Матрица, представляющая эту трансформацию. Объект матрицы живой, то есть любые изменения, внесённые в объект SVGTransform, сразу отражаются в объекте матрицы и наоборот. Если объект матрицы изменяется напрямую (т.е. без использования методов интерфейса SVGTransform), тип SVGTransform меняется на SVG_TRANSFORM_MATRIX. Для SVG_TRANSFORM_MATRIX матрица содержит значения a, b, c, d, e, f, заданные пользователем. Для SVG_TRANSFORM_TRANSLATE e и f представляют величины трансляции (a=1, b=0, c=0, d=1). Для SVG_TRANSFORM_SCALE a и d представляют коэффициенты масштабирования (b=0, c=0, e=0, f=0). Для SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY a, b, c и d представляют матрицу, которая даст указанный наклон (e=0 и f=0). Для SVG_TRANSFORM_ROTATE a, b, c, d, e и f вместе представляют матрицу, которая даст указанное вращение. Когда вращение происходит вокруг центральной точки (0, 0), e и f будут нулевыми. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) Тип значения, указанный одной из констант SVG_TRANSFORM_*, определённых в этом интерфейсе. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Устанавливает тип трансформации в SVG_TRANSFORM_MATRIX, с параметром matrix, определяющим новую трансформацию. Значения из параметра matrix копируются, параметр matrix не заменяет SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Устанавливает тип трансформации в SVG_TRANSFORM_ROTATE, с параметром angle, определяющим угол вращения, и параметрами cx и cy, определяющими необязательный центр вращения. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Устанавливает тип трансформации в SVG_TRANSFORM_SCALE, с параметрами sx и sy, определяющими коэффициенты масштабирования. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Устанавливает тип трансформации в SVG_TRANSFORM_SKEWX, с параметром angle, определяющим величину наклона. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Устанавливает тип трансформации в SVG_TRANSFORM_SKEWY, с параметром angle, определяющим величину наклона. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Устанавливает тип трансформации в SVG_TRANSFORM_TRANSLATE, с параметрами tx и ty, определяющими величины трансляции. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Трансформация 'matrix(…)'. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Трансформация 'rotate(…)'. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Трансформация 'scale(…)'. |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Трансформация 'skewX(…)'. |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Трансформация 'skewY(…)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Трансформация 'translate(…)'. |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Тип единицы не является одним из предопределённых типов. Недопустимо пытаться определить новое значение этого типа или пытаться переключить существующее значение на этот тип. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
