---
title: dispatch_event method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /python-net/aspose.html/htmltablerowelement/dispatch_event/
is_root: false
---

## dispatch_event {#aspose.html.dom.events.Event}

Dispatches an Event at the specified [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget), (synchronously) invoking
the affected EventListeners in the appropriate order. 
The normal event processing rules (including the capturing and optional bubbling phase) also apply to events 
dispatched manually with [`IEventTarget.dispatch_event`](/html/python-net/aspose.html.dom.events/ieventtarget/dispatch_event).


### Returns 


The return value of [`EventTarget.dispatch_event`](/html/python-net/aspose.html.dom/eventtarget/dispatch_event) indicates whether any of the listeners which handled the event called [`Event.prevent_default`](/html/python-net/aspose.html.dom.events/event/prevent_default).
If [`Event.prevent_default`](/html/python-net/aspose.html.dom.events/event/prevent_default) was called the value is false, else the value is true.


```python
def dispatch_event(self, event):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| event | aspose.html.dom.events.Event | Specifies the event type, behavior, and contextual information to be used in processing the event. |
### Remarks

Events dispatched in this manner will have the same capturing and bubbling behavior as events dispatched directly by the implementation.
The target of the event is the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which [`EventTarget.dispatch_event`](/html/python-net/aspose.html.dom/eventtarget/dispatch_event) is called.### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) |  |





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`HTMLTableRowElement`](/html/python-net/aspose.html/htmltablerowelement)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
