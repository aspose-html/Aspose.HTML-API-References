---
title: "TimeEvent.InitTimeEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод TimeEvent. Метод initTimeEvent используется для инициализации значения TimeEvent, созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того, как TimeEvent будет отправлен через метод dispatchEvent, хотя при необходимости его можно вызвать несколько раз в течение этой фазы. Если вызвать его несколько раз, окончательный вызов имеет приоритет"
type: docs

url: /ru/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Метод initTimeEvent используется для инициализации значения TimeEvent, созданного через интерфейс DocumentEvent. Этот метод может быть вызван только до того, как TimeEvent будет отправлен с помощью метода dispatchEvent, хотя при необходимости его можно вызвать несколько раз в этом этапе. Если вызвано несколько раз, приоритет имеет последний вызов.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| typeArg | String | Указывает тип события. |
| viewArg | IAbstractView | Указывает AbstractView события. |
| detailArg | Int64 | Указывает detail события. |

### См. также

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
