---
title: remove_event_listener method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 340
url: /aspose.html.dom.svg/svggradientelement/remove_event_listener/
is_root: false
---

## remove_event_listener {#str-aspose.html.dom.events.IEventListener}

This method allows the removal of event listeners from the event target.
If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.
Event Listeners can never be invoked after being removed.



```python
def remove_event_listener(self, type, listener):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | str | Specifies the event type of the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) being removed. |
| listener | aspose.html.dom.events.IEventListener | The [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) parameter indicates the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) to be removed. |


## remove_event_listener {#str-aspose.html.dom.events.IEventListener-bool}

This method allows the removal of event listeners from the event target.
If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.
Event Listeners can never be invoked after being removed.



```python
def remove_event_listener(self, type, listener, use_capture):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | str | Specifies the event type of the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) being removed. |
| listener | aspose.html.dom.events.IEventListener | The [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) parameter indicates the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) to be removed. |
| use_capture | bool | Specifies whether the EventListener being removed was registered as a capturing listener or not.<br/>If a listener was registered twice, one with capture and one without, each must be removed separately.<br/>Removal of a capturing listener does not affect a non-capturing version of the same listener, and vice versa. |



### See Also
* module [`aspose.html.dom.svg`](../../)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`SVGGradientElement`](/html/python-net/aspose.html.dom.svg/svggradientelement)
