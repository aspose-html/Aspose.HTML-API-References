---
title: EventTarget.DispatchEvent
second_title: Aspose.HTML for Java API Reference
description: EventTarget method. Dispatches an Event at the specified EventTarget synchronously invoking the affected EventListeners in the appropriate order. The normal event processing rules including the capturing and optional bubbling phase also apply to events dispatched manually with dispatchEvent
type: docs
weight: 30
url: /java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Dispatches an Event at the specified [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Type | Description |
| --- | --- | --- |
| event | Event | Specifies the event type, behavior, and contextual information to be used in processing the event. |

### Return Value

The return value of indicates whether any of the listeners which handled the event called. If was called the value is false, else the value is true.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Remarks

Events dispatched in this manner will have the same capturing and bubbling behavior as events dispatched directly by the implementation. The target of the event is the on which is called.

### See Also

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
