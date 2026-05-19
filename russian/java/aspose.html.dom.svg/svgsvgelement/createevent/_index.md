---
title: "SVGSVGElement.CreateEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGSVGElement. Создаёт объект Event типа, поддерживаемого реализацией."
type: docs

url: /ru/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Создаёт [`Event`](../../../com.aspose.html.dom.events/event/) типа, поддерживаемого реализацией.

```java
public Event CreateEvent(String eventType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Параметр eventType указывает тип интерфейса [`Event`](../../../com.aspose.html.dom.events/event/) , который необходимо создать. Если указанный интерфейс [`Event`](../../../com.aspose.html.dom.events/event/) поддерживается реализацией, этот метод вернёт новый[`Event`](../../../com.aspose.html.dom.events/event/) запрошенного типа интерфейса. Если [`Event`](../../../com.aspose.html.dom.events/event/) должен быть отправлен с помощью метода [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) , после создания необходимо вызвать соответствующий[`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) метод для инициализации значений [`Event`](../../../com.aspose.html.dom.events/event/). |

### Возвращаемое значение

Недавно созданный [`Event`](../../../com.aspose.html.dom.events/event/)

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если реализация не поддерживает запрошенный тип интерфейса [`Event`](../../../com.aspose.html.dom.events/event/) |

### См. также

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
