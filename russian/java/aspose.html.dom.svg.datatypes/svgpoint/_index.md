---
title: "SVGPoint класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint класс. Многие интерфейсы SVG DOM ссылаются на объекты класса SVGPoint. SVGPoint представляет собой пару координат x y. При использовании в матричных операциях SVGPoint рассматривается как вектор формы x y 1. Если объект SVGRect помечен как только для чтения, попытка присвоить значение одному из его атрибутов приведёт к выбросу исключения."
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

Во многих интерфейсах SVG DOM имеются ссылки на объекты класса SVGPoint. SVGPoint представляет собой пару координат (x, y). При использовании в матричных операциях SVGPoint рассматривается как вектор формы: [x] [y] [1]. Если объект SVGRect объявлен только для чтения, попытка присвоить значение одному из его атрибутов приведёт к выбросу исключения.

```java
public class SVGPoint : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | Координата X. |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Координата Y. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Применяет 2x3 матричное преобразование к этому объекту SVGPoint и возвращает новый, преобразованный объект SVGPoint: newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
