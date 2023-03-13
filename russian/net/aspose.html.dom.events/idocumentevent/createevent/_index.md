---
title: IDocumentEvent.CreateEvent
second_title: Справочник по Aspose.HTML для .NET API
description: IDocumentEvent метод. СоздаетEvent типа поддерживаемого реализацией.
type: docs
weight: 10
url: /ru/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Создает[`Event`](../../event/) типа, поддерживаемого реализацией.

```csharp
public Event CreateEvent(string eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип[`Event`](../../event/) интерфейс, который нужно создать.  Если[`Event`](../../event/)указанный интерфейс поддерживается реализацией, этот метод вернет new [`Event`](../../event/) запрошенного типа интерфейса. Если[`Event`](../../event/)должен быть отправлен через[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) метод соответствующий [`InitEvent`](../../event/initevent/) метод должен быть вызван после создания, чтобы инициализировать[`Event`](../../event/) значения s. |

### Возвращаемое значение

Недавно созданный[`Event`](../../event/)

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если реализация не поддерживает тип[`Event`](../../event/) запрошенный интерфейс |

### Смотрите также

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* пространство имен [Aspose.Html.Dom.Events](../../idocumentevent/)
* сборка [Aspose.HTML](../../../)


