---
title: "Event.StopPropagation"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Event. Метод StopPropagation используется для предотвращения дальнейшего распространения события во время потока событий."
type: docs

url: /ru/java/com.aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

Метод `StopPropagation` используется для предотвращения дальнейшего распространения события во время потока событий.

```java
public void StopPropagation()
```

## Примечания

Если этот метод вызывается любым [`IEventListener`](../../ieventlistener/), событие перестанет распространяться по дереву. Событие завершит доставку всем слушателям текущего [`IEventTarget`](../../ieventtarget/) до остановки потока событий. Этот метод может быть использован на любой стадии потока событий.

### См. также

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
