---
title: IEventTarget class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/aspose.html.dom.events/ieventtarget/
is_root: false
---

## IEventTarget class

The [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) interface is implemented by all Nodes in an implementation which supports the DOM Event Model.
Therefore, this interface can be obtained by using binding-specific casting methods on an instance of the Node interface.
The interface allows registration and removal of Event Listeners on an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) and dispatch of events to that [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget).



The IEventTarget type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the registration of event listeners on the event target. |
| [add_event_listener](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the registration of event listeners on the event target. |
| [remove_event_listener](/html/python-net/aspose.html.dom.events/ieventtarget/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [remove_event_listener](/html/python-net/aspose.html.dom.events/ieventtarget/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [dispatch_event](/html/python-net/aspose.html.dom.events/ieventtarget/dispatch_event/#aspose.html.dom.events.Event) | This method allows the dispatch of events into the implementations event model. |



### See Also
* module [`aspose.html.dom.events`](..)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
