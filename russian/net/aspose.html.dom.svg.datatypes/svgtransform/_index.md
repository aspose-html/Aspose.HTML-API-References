---
title: SVGTransform
second_title: Справочник по Aspose.HTML для .NET API
description: SVGTransform  это интерфейс для одного из преобразований компонентов в SVGTransformList таким образом объект SVGTransform соответствует одному компоненту например масштаб  или матрица  в спецификации атрибута преобразование.
type: docs
weight: 1410
url: /ru/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform — это интерфейс для одного из преобразований компонентов в SVGTransformList; таким образом, объект SVGTransform соответствует одному компоненту (например, «масштаб (…)» или «матрица (…)») в спецификации атрибута «преобразование».

```csharp
public class SVGTransform : SVGValueType
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle) { get; } | Удобный атрибут для SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY. Он удерживает заданный угол. Для SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE и SVG_TRANSFORM_SCALE угол будет равен нулю. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix) { get; } | Матрица, представляющая это преобразование. Объект матрицы является активным, что означает, что любые изменения, внесенные в объект SVGTransform, немедленно отражаются в объекте матрицы и наоборот. Если объект матрицы изменяется напрямую (т. е. без использования методов самого интерфейса SVGTransform), то тип SVGTransform изменяется на SVG_TRANSFORM_MATRIX. Для SVG_TRANSFORM_MATRIX матрица содержит значения a, b, c, d, e, f, предоставленные пользователем. Для SVG_TRANSFORM_TRANSLATE e и f представляют суммы перевода (a = 1, b = 0, c = 0 и d = 1). Для SVG_TRANSFORM_SCALE a и d представляют величины шкалы (b = 0, c = 0, e = 0 и f = 0). Для SVG_TRANSFORM_SKEWX и SVG_TRANSFORM_SKEWY a, b, c и d представляют матрицу, которая приведет к данному перекосу (e = 0 и f = 0). Для SVG_TRANSFORM_ROTATE a, b, c, d, e и f вместе представляют матрицу, которая приведет к заданному вращению. Когда вращение происходит вокруг центральной точки (0, 0), e и f будет нулевым. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type) { get; } | Тип значения, заданный одной из констант SVG_TRANSFORM_*, определенных в этом интерфейсе. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose)() | Освобождает неуправляемые и (необязательно) управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix)(SVGMatrix) | Устанавливает тип преобразования в SVG_TRANSFORM_MATRIX с матрицей параметров, определяющей новое преобразование. Копируются значения из матрицы параметров, параметр матрицы не заменяет SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate)(float, float, float) | Устанавливает тип преобразования на SVG_TRANSFORM_ROTATE, с параметром angle, определяющим угол поворота, и параметрами cx и cy, определяющими необязательный центр вращения. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale)(float, float) | Устанавливает тип преобразования в SVG_TRANSFORM_SCALE, с параметрами sx и sy, определяющими величины масштаба. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx)(float) | Устанавливает тип преобразования SVG_TRANSFORM_SKEWX с параметром angle, определяющим величину перекоса. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy)(float) | Устанавливает тип преобразования на SVG_TRANSFORM_SKEWY с параметром angle, определяющим величину перекоса. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate)(float, float) | Устанавливает тип преобразования в SVG_TRANSFORM_TRANSLATE с параметрами tx и ty, определяющими суммы перевода. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix) | Преобразование «матрица (…)». |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate) | Преобразование 'rotate(…)'. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale) | Преобразование «масштаб(…)». |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx) | Преобразование 'skewX(…)'. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy) | Преобразование 'skewY(…)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate) | Преобразование "перевести(…)". |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown) | Тип юнита не является одним из предопределенных типов. Недопустимо пытаться определить новое значение этого типа или пытаться переключить существующее значение на этот тип. |

### Смотрите также

* class [SVGValueType](../svgvaluetype)
* пространство имен [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
