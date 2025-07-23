---
title: EventTarget.DispatchEvent
second_title: Aspose.HTML for .NET API Reference
description: EventTarget DispatchEvent method. Dispatches an Event at the specified IEventTarget synchronously invoking the affected EventListeners in the appropriate order. The normal event processing rules including the capturing and optional bubbling phase also apply to events dispatched manually with DispatchEvent
type: docs
weight: 30
url: /net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Dispatches an Event at the specified [`IEventTarget`](../../../aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/).

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Type | Description |
| --- | --- | --- |
| event | Event | Specifies the event type, behavior, and contextual information to be used in processing the event. |

### Return Value

The return value of `DispatchEvent` indicates whether any of the listeners which handled the event called [`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/). If [`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) was called the value is false, else the value is true.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) |  |

## Remarks

Events dispatched in this manner will have the same capturing and bubbling behavior as events dispatched directly by the implementation. The target of the event is the [`EventTarget`](../) on which `DispatchEvent` is called.

### See Also

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
