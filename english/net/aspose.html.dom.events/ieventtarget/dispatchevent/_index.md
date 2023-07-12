---
title: IEventTarget.DispatchEvent
second_title: Aspose.HTML for .NET API Reference
description: IEventTarget method. Dispatches an Event at the specified EventTarget synchronously invoking the affected EventListeners in the appropriate order. The normal event processing rules including the capturing and optional bubbling phase also apply to events dispatched manually with dispatchEvent
type: docs
weight: 20
url: /net/aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Dispatches an Event at the specified EventTarget, (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with dispatchEvent().

```csharp
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
| [DOMException](../../../aspose.html.dom/domexception/) | Exceptions thrown by event handlers are reported as uncaught exceptions. The event handlers run on a nested callstack; they block the caller until they complete, but exceptions do not propagate to the caller. |

## Remarks

Events dispatched in this manner will have the same capturing and bubbling behavior as events dispatched directly by the implementation. The target of the event is the on which is called.

### See Also

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Html.Dom.Events](../../ieventtarget/)
* assembly [Aspose.HTML](../../../)
