---
title: Aspose.Html.Dom.Events
second_title: Aspose.HTML for .NET API Reference
description: The Aspose.Html.Dom.Events namespace provides objects for any events related DOM updating. It includes subscription to specific contextual information observation associated with event as well as custom events construction
type: docs
weight: 120
url: /net/aspose.html.dom.events/
---
The **Aspose.Html.Dom.Events** namespace provides objects for any events related DOM updating. It includes subscription to specific contextual information observation associated with event as well as custom events construction.

## Classes

| Class | Description |
| --- | --- |
| [CustomEvent](./customevent/) | Events using the CustomEvent interface can be used to carry custom data. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | The DocumentLoadErrorEvent occurres when the requested resource is not available. |
| [DOMEventHandler](./domeventhandler/) | Represents a generic callback delegate for Document Object Model (DOM) event handling. |
| [ErrorEvent](./errorevent/) | The ErrorEvent provides contextual information about an errors that occurred during runtime. |
| [Event](./event/) | The is used to provide contextual information about an event to the handler processing the event. |
| [FocusEvent](./focusevent/) | The FocusEvent interface provides specific contextual information associated with Focus events. |
| [InputEvent](./inputevent/) | Input events are sent as notifications whenever the DOM is being updated. |
| [KeyboardEvent](./keyboardevent/) | The KeyboardEvent interface provides specific contextual information associated with keyboard devices. Each keyboard event references a key using a value. Keyboard events are commonly directed at the element that has the focus. |
| [MouseEvent](./mouseevent/) | The MouseEvent interface provides specific contextual information associated with Mouse events. |
| [UIEvent](./uievent/) | The UIEvent interface provides specific contextual information associated with User Interface events. |
| [WheelEvent](./wheelevent/) | The WheelEvent interface provides specific contextual information associated with wheel events. To create an instance of the WheelEvent interface, use the WheelEvent constructor, passing an optional WheelEventInit dictionary. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | The DocumentEvent interface provides a mechanism by which the user can create an Event of a type supported by the implementation. It is expected that the DocumentEvent interface will be implemented on the same object which implements the Document interface in an implementation which supports the Event model. |
| [IEventListener](./ieventlistener/) | The interface is the primary method for handling events. Users implement the interface and register their listener on an using the method. The users should also remove their from its after they have completed using the listener. |
| [IEventTarget](./ieventtarget/) | The EventTarget interface is implemented by all Nodes in an implementation which supports the DOM Event Model. Therefore, this interface can be obtained by using binding-specific casting methods on an instance of the Node interface. The interface allows registration and removal of Event Listeners on an and dispatch of events to that. |
