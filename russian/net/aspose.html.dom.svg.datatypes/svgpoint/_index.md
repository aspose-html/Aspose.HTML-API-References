---
title: Class SVGPoint
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Svg.DataTypes.SVGPoint сорт. Многие интерфейсы SVG DOM ссылаются на объекты класса SVGPoint. SVGPoint  это пара координат x y. При использовании в матричных операциях SVGPoint рассматривается как вектор вида x y 1 Если объект SVGRect обозначен как доступный только для чтения то попытка присвоить один из его атрибутов приведет к привести к возникновению исключения.
type: docs
weight: 1250
url: /ru/net/aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

Многие интерфейсы SVG DOM ссылаются на объекты класса SVGPoint. SVGPoint — это пара координат (x, y). При использовании в матричных операциях SVGPoint рассматривается как вектор вида: [x] [y] [1] Если объект SVGRect обозначен как доступный только для чтения, то попытка присвоить один из его атрибутов приведет к привести к возникновению исключения.

```csharp
public class SVGPoint : SVGValueType
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [X](../../aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | Координата X. |
| [Y](../../aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Координата Y. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и (необязательно) управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [MatrixTransform](../../aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Применяет матричное преобразование 2x3 к этому объекту SVGPoint и возвращает новый, преобразованный объект SVGPoint: newpoint = matrix* thispoint |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgpoint/tostring/)() | ВозвращаетString который представляет этот экземпляр. |

### Смотрите также

* class [SVGValueType](../svgvaluetype/)
* пространство имен [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* сборка [Aspose.HTML](../../)


