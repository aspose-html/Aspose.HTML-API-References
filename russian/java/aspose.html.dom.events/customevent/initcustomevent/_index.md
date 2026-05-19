---
title: "CustomEvent.InitCustomEvent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод CustomEvent. /// Метод InitEvent используется для инициализации значения события, созданного через интерфейс IDocumentEvent"
type: docs

url: /ru/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Метод [`InitEvent`](../../event/initevent/) используется для инициализации значения [`Event`](../../event/), созданного через интерфейс [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | String | Тип события. |
| bubbles | Boolean | если установлено `true` [bubbles]. |
| cancelable | Boolean | если установлено `true` [cancelable]. |
| detail | Объект | Пользовательские данные. |

## Примечания

Этот метод может быть вызван только до того, как событие было отправлено через метод [`DispatchEvent`](../../ieventtarget/dispatchevent/), хотя при необходимости его можно вызывать несколько раз в этом этапе. При множественных вызовах приоритет имеет последний вызов. Если вызван из подкласса интерфейса Event, изменяются только значения, указанные в методе initEvent, все остальные атрибуты остаются без изменений.

### См. также

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
