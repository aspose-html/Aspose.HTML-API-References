---
title: EventTarget Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.EventTarget class. The EventTarget interface is implemented by objects that can receive events and may have listeners for them. In other words any target of events implements the three methods associated with this interface
type: docs
weight: 870
url: /net/aspose.html.dom/eventtarget/
---
## EventTarget class

The EventTarget interface is implemented by objects that can receive events and may have listeners for them. In other words, any target of events implements the three methods associated with this interface.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | The addEventListener() method of the `EventTarget `interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |

### See Also

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* namespace [Aspose.Html.Dom](../../aspose.html.dom/)
* assembly [Aspose.HTML](../../)
