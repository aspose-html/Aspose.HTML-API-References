---
title: Interface ICSSStyleDeclaration
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration интерфейс. Интерфейс CSSStyleDeclaration представляет собой единый блок объявления CSS. Этот интерфейс можно использовать для определения свойств стиля установленных в данный момент в блоке или для явной установки свойств стиля в блоке.
type: docs
weight: 490
url: /ru/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Интерфейс CSSStyleDeclaration представляет собой единый блок объявления CSS. Этот интерфейс можно использовать для определения свойств стиля, установленных в данный момент в блоке, или для явной установки свойств стиля в блоке.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | Поддающееся разбору текстовое представление блока объявлений (исключая окружающие фигурные скобки). Установка этого атрибута приведет к синтаксическому анализу нового значения и сбросу всех свойств в блоке объявлений, включая удаление или добавление свойств. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Используется для получения свойств, которые были явно установлены в этом блоке объявлений. Порядок свойств, полученных с помощью этого метода, не обязательно должен быть порядком, в котором они были заданы. Этот метод можно использовать для перебора всех свойств в этом блоке объявлений. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | Количество свойств, которые были явно установлены в этом блоке объявления. Диапазон допустимых индексов: от 0 до длины 1 включительно. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | Правило CSS, содержащее этот блок объявления, или null, если это CSSStyleDeclaration не присоединено к CSSRule. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Используется для получения объектного представления значения свойства CSS, если оно было явно установлено в этом блоке объявления. Этот метод возвращает null, если свойство является сокращенным свойством. К сокращенным значениям свойств можно получить доступ и изменить их только как строки, используя методы getPropertyValue и setProperty. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Используется для получения приоритета свойства CSS (например, квалификатора «важный»), если свойство было явно установлено в этом блоке объявлений. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Используется для получения значения свойства CSS, если оно было явно задано в этом блоке объявления. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | Используется для удаления свойства CSS, если оно было явно задано в этом блоке объявления. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Используется для установки значения свойства с приоритетом по умолчанию в этом блоке объявлений. Приоритет по умолчанию не является «важным», т.е. String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Используется для установки значения свойства и приоритета в этом блоке объявления. |

### Смотрите также

* interface [ICSS2Properties](../icss2properties/)
* пространство имен [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* сборка [Aspose.HTML](../../)


