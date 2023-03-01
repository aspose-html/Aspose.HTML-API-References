---
title: SVGSVGElement.CreateEvent
second_title: Справочник по Aspose.HTML для .NET API
description: SVGSVGElement метод. СоздаетEvent типа поддерживаемого реализацией.
type: docs
weight: 110
url: /ru/net/aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Создает[`Event`](../../../aspose.html.dom.events/event/) типа, поддерживаемого реализацией.

```csharp
public Event CreateEvent(string eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип[`Event`](../../../aspose.html.dom.events/event/) интерфейс, который нужно создать.  Если[`Event`](../../../aspose.html.dom.events/event/)указанный интерфейс поддерживается реализацией, этот метод вернет new [`Event`](../../../aspose.html.dom.events/event/) запрошенного типа интерфейса. Если[`Event`](../../../aspose.html.dom.events/event/)должен быть отправлен через[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) метод соответствующий [`InitEvent`](../../../aspose.html.dom.events/event/initevent/) метод должен быть вызван после создания, чтобы инициализировать[`Event`](../../../aspose.html.dom.events/event/) значения s. |

### Возвращаемое значение

Недавно созданный[`Event`](../../../aspose.html.dom.events/event/)

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если реализация не поддерживает тип[`Event`](../../../aspose.html.dom.events/event/) запрошенный интерфейс |

### Смотрите также

* class [Event](../../../aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* сборка [Aspose.HTML](../../../)


