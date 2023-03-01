---
title: Class CSSValue
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Css.CSSValue сорт. Представляет простое или сложное значение. Объект CSSValue встречается только в контексте свойства CSS.
type: docs
weight: 340
url: /ru/net/aspose.html.dom.css/cssvalue/
---
## CSSValue class

Представляет простое или сложное значение. Объект CSSValue встречается только в контексте свойства CSS.

```csharp
public abstract class CSSValue : DOMObject
```

## Характеристики

| Имя | Описание |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Строковое представление текущего значения. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Код, определяющий тип значения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Определяет, является ли указанныйObject равен этому экземпляру. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Возвращает хэш-код для этого экземпляра. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | ВозвращаетString который представляет этот экземпляр. |
| [operator ==](../../aspose.html.dom.css/cssvalue/op_equality/) | Реализует оператор ==. |
| [operator !=](../../aspose.html.dom.css/cssvalue/op_inequality/) | Реализует оператор !=. |

## Поля

| Имя | Описание |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.html.dom.css/cssvalue/css_custom/) | Значение является пользовательским значением. |
| const [CSS_INHERIT](../../aspose.html.dom.css/cssvalue/css_inherit/) | Значение унаследовано, а cssText содержит «наследовать». |
| const [CSS_PRIMITIVE_VALUE](../../aspose.html.dom.css/cssvalue/css_primitive_value/) | Значение является примитивным значением, и экземпляр интерфейса CSSPrimitiveValue можно получить с помощью методов приведения, специфичных для привязки, для этого экземпляра интерфейса CSSValue. |
| const [CSS_VALUE_LIST](../../aspose.html.dom.css/cssvalue/css_value_list/) | Значение представляет собой список CSSValue, а экземпляр интерфейса CSSValueList можно получить с помощью методов приведения, специфичных для привязки, для этого экземпляра интерфейса CSSValue. |

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject/)
* пространство имен [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* сборка [Aspose.HTML](../../)


