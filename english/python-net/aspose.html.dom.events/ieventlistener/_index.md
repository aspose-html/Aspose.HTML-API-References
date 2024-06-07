---
title: IEventListener class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.html.dom.events/ieventlistener/
is_root: false
---

## IEventListener class

The [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) interface is the primary method for handling events.
Users implement the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) interface and register their listener on an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) using the [`EventTarget.add_event_listener`](/html/python-net/aspose.html.dom/eventtarget/add_event_listener) method.
The users should also remove their [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) from its [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) after they have completed using the listener.



The IEventListener type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [handle_event](/html/python-net/aspose.html.dom.events/ieventlistener/handle_event/#aspose.html.dom.events.Event) | This method is called whenever an event occurs of the type for which the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) interface was registered. |



### Remarks 


When a Node is copied using the cloneNode method the Event Listeners attached to the source Node are not attached to the copied Node.
If the user wishes the same Event Listeners to be added to the newly created copy the user must add them manually.

### See Also
* module [`aspose.html.dom.events`](..)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
