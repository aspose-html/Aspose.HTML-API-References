---
title: add_event_listener method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.html.dom/text/add_event_listener/
is_root: false
---

## add_event_listener {#str-aspose.html.dom.events.IEventListener}

This method allows the registration of event listeners on the event target.



```python
def add_event_listener(self, type, listener):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | str | The event type for which the user is registering |
| listener | aspose.html.dom.events.IEventListener | Takes an interface implemented by the user which contains the methods to be called when the event occurs. |
### Remarks

If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is added to an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered
by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase.




If multiple identical Event Listeners are registered on the same [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) with the same parameters the duplicate instances are discarded.
They do not cause the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) to be called twice and since they are discarded they do not need to be removed with the
[`EventTarget.remove_event_listener`](/html/python-net/aspose.html.dom/eventtarget/remove_event_listener)
method.

## add_event_listener {#str-aspose.html.dom.events.IEventListener-bool}

This method allows the registration of event listeners on the event target.



```python
def add_event_listener(self, type, listener, use_capture):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | str | The event type for which the user is registering |
| listener | aspose.html.dom.events.IEventListener | Takes an interface implemented by the user which contains the methods to be called when the event occurs. |
| use_capture | bool | If true, useCapture indicates that the user wishes to initiate capture.<br/>After initiating capture, all events of the specified type will be dispatched to the registered<br/>[`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)<br/>before being dispatched to any Event Targets beneath them in the tree.<br/>Events which are bubbling upward through the tree will not trigger an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) designated to use capture. |
### Remarks

If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is added to an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered
by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase.




If multiple identical Event Listeners are registered on the same [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) with the same parameters the duplicate instances are discarded.
They do not cause the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) to be called twice and since they are discarded they do not need to be removed with the
[`EventTarget.remove_event_listener`](/html/python-net/aspose.html.dom/eventtarget/remove_event_listener)
method.


### See Also
* module [`aspose.html.dom`](../../)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`Text`](/html/python-net/aspose.html.dom/text)
