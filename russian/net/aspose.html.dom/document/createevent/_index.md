---
title: CreateEvent
second_title: Справочник по Aspose.HTML для .NET API
description: СоздаетEventaspose.html.dom.events/eventтипа поддерживаемого реализацией.
type: docs
weight: 880
url: /ru/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Создает[`Event`](../../../aspose.html.dom.events/event)типа, поддерживаемого реализацией.

```csharp
public Event CreateEvent(string eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип[`Event`](../../../aspose.html.dom.events/event)создаваемый интерфейс.  Если указанный интерфейс[`Event`](../../../aspose.html.dom.events/event)поддерживается реализацией этот метод будет возвращать новый[`Event`](../../../aspose.html.dom.events/event)запрошенного типа интерфейса. Если[`Event`](../../../aspose.html.dom.events/event)должен быть отправлен через[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent)метод соответствующий[`InitEvent`](../../../aspose.html.dom.events/event/initevent) метод должен быть вызван после создания, чтобы инициализировать значения[`Event`](../../../aspose.html.dom.events/event). |

### Возвращаемое значение

Вновь созданный[`Event`](../../../aspose.html.dom.events/event)

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception) | NOT_SUPPORTED_ERR:Возникает, если реализация не поддерживает тип[`Event`](../../../aspose.html.dom.events/event)запрашиваемый интерфейс |

### Смотрите также

* class [Event](../../../aspose.html.dom.events/event)
* class [Document](../../document)
* пространство имен [Aspose.Html.Dom](../../document)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
