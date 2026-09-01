---
title: "Event.InitEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Event. Метод InitEvent используется для инициализации значения события, созданного через интерфейс theIDocumentEvent."
type: docs

url: /ru/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Метод `InitEvent` используется для инициализации значения [`Event`](../), созданного через интерфейс [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | String | Тип события. |
| bubbles | Boolean | если установлено `true` [bubbles]. |
| cancelable | Boolean | если установлено `true` [cancelable]. |

## Примечания

Этот метод может быть вызван только до того, как событие было отправлено через метод [`DispatchEvent`](../../ieventtarget/dispatchevent/), хотя при необходимости его можно вызывать несколько раз в этой фазе. При множественных вызовах приоритет имеет последний вызов. Если вызвать его из подкласса интерфейса Event, изменяются только значения, указанные в методе initEvent, все остальные атрибуты остаются без изменений.

### См. также

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
