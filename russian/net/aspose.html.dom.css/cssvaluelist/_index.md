---
title: Class CSSValueList
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Css.CSSValueList сорт. Интерфейс CSSValueList обеспечивает абстракцию упорядоченного набора значений CSS.
type: docs
weight: 350
url: /ru/net/aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

Интерфейс CSSValueList обеспечивает абстракцию упорядоченного набора значений CSS.

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Инициализирует новый экземпляр`CSSValueList` класс. |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | Инициализирует новый экземпляр`CSSValueList` класс. |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | Инициализирует новый экземпляр`CSSValueList` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [CSSText](../../aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | Строковое представление текущего значения. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Код, определяющий тип значения. |
| [Item](../../aspose.html.dom.css/cssvaluelist/item/) { get; } | Получает[`CSSValue`](../cssvalue/) по указанному индексу. |
| [Length](../../aspose.html.dom.css/cssvaluelist/length/) { get; } | Количество CSSValues в списке. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Определяет, является ли указанныйObject равен этому экземпляру. |
| [GetEnumerator](../../aspose.html.dom.css/cssvaluelist/getenumerator/)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Возвращает хэш-код для этого экземпляра. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvaluelist/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | ВозвращаетString который представляет этот экземпляр. |

### Смотрите также

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* пространство имен [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* сборка [Aspose.HTML](../../)


