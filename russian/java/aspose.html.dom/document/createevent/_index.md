---
title: "Document.CreateEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Создает объект Event типа, поддерживаемого реализацией."
type: docs

url: /ru/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Создаёт [`Event`](../../../com.aspose.html.dom.events/event/) типа, поддерживаемого реализацией.

```java
public Event CreateEvent(String eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип интерфейса [`Event`](../../../com.aspose.html.dom.events/event/), который необходимо создать. Если указанный интерфейс [`Event`](../../../com.aspose.html.dom.events/event/) поддерживается реализацией, этот метод вернёт новый [`Event`](../../../com.aspose.html.dom.events/event/) запрошенного типа интерфейса. Если [`Event`](../../../com.aspose.html.dom.events/event/) должен быть отправлен с помощью метода [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/), после создания необходимо вызвать соответствующий метод [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/), чтобы инициализировать значения [`Event`](../../../com.aspose.html.dom.events/event/). |

### Возвращаемое значение

Недавно созданный [`Event`](../../../com.aspose.html.dom.events/event/)

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если реализация не поддерживает запрошенный тип интерфейса [`Event`](../../../com.aspose.html.dom.events/event/) |

### См. также

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
