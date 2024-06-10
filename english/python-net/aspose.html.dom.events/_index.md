---
title: aspose.html.dom.events
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/aspose.html.dom.events/
is_root: false
---

The **Aspose.Html.Dom.Events**  namespace provides objects for
any events related DOM updating. It includes subscription to
specific contextual information observation
associated with event as well as custom events construction.

### Classes
| Class | Description |
| :- | :- |
| [`CustomEvent`](/html/python-net/aspose.html.dom.events/customevent) | Events using the CustomEvent interface can be used to carry custom data. |
| [`DocumentLoadErrorEvent`](/html/python-net/aspose.html.dom.events/documentloaderrorevent) | The [`DocumentLoadErrorEvent`](/html/python-net/aspose.html.dom.events/documentloaderrorevent) occurres when the requested resource is not available. |
| [`ErrorEvent`](/html/python-net/aspose.html.dom.events/errorevent) | The [`ErrorEvent`](/html/python-net/aspose.html.dom.events/errorevent) provides contextual information about an errors that occurred during runtime. |
| [`Event`](/html/python-net/aspose.html.dom.events/event) | The [`Event`](/html/python-net/aspose.html.dom.events/event) is used to provide contextual information about an event to the handler processing the event. |
| [`FocusEvent`](/html/python-net/aspose.html.dom.events/focusevent) | The FocusEvent interface provides specific contextual information associated with Focus events. |
| [`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent) | The [`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent) interface provides a mechanism by which the user can create an [`Event`](/html/python-net/aspose.html.dom.events/event) of a type supported by the implementation. |
| [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) | The [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) interface is the primary method for handling events.<br/>Users implement the [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) interface and register their listener on an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) using the [`EventTarget.add_event_listener`](/html/python-net/aspose.html.dom/eventtarget/add_event_listener) method.<br/>The users should also remove their [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) from its [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) after they have completed using the listener. |
| [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) | The [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) interface is implemented by all Nodes in an implementation which supports the DOM Event Model.<br/>Therefore, this interface can be obtained by using binding-specific casting methods on an instance of the Node interface.<br/>The interface allows registration and removal of Event Listeners on an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) and dispatch of events to that [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget). |
| [`InputEvent`](/html/python-net/aspose.html.dom.events/inputevent) | Input events are sent as notifications whenever the DOM is being updated. |
| [`KeyboardEvent`](/html/python-net/aspose.html.dom.events/keyboardevent) | The KeyboardEvent interface provides specific contextual information associated with keyboard devices. Each keyboard event references a key using a value. Keyboard events are commonly directed at the element that has the focus. |
| [`MouseEvent`](/html/python-net/aspose.html.dom.events/mouseevent) | The MouseEvent interface provides specific contextual information associated with Mouse events. |
| [`UIEvent`](/html/python-net/aspose.html.dom.events/uievent) | The UIEvent interface provides specific contextual information associated with User Interface events. |
| [`WheelEvent`](/html/python-net/aspose.html.dom.events/wheelevent) | The WheelEvent interface provides specific contextual information associated with wheel events. To create an instance of the WheelEvent interface, use the WheelEvent constructor, passing an optional WheelEventInit dictionary. |


