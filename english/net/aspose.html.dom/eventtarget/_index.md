---
title: EventTarget Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.EventTarget class. The EventTarget interface is implemented by all Nodes in an implementation which supports the DOM Event Model. Therefore this interface can be obtained by using binding-specific casting methods on an instance of the Node interface. The interface allows registration and removal of Event Listeners on an EventTarget and dispatch of events to that IEventTarget
type: docs
weight: 890
url: /net/aspose.html.dom/eventtarget/
---
## EventTarget class

The `EventTarget` interface is implemented by all Nodes in an implementation which supports the DOM Event Model. Therefore, this interface can be obtained by using binding-specific casting methods on an instance of the Node interface. The interface allows registration and removal of Event Listeners on an `EventTarget` and dispatch of events to that [`IEventTarget`](../../aspose.html.dom.events/ieventtarget/).

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Constructors

| Name | Description |
| --- | --- |
| [EventTarget](eventtarget/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/)*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(*string, [DOMEventHandler](../../aspose.html.dom.events/domeventhandler/), bool*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/), bool*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.html.dom.events/event/)*) | Dispatches an Event at the specified [`IEventTarget`](../../aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`DispatchEvent`](../../aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object Type. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/)*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an `EventTarget` while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(*string, [DOMEventHandler](../../aspose.html.dom.events/domeventhandler/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an `EventTarget` while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an `EventTarget` while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |

### See Also

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* namespace [Aspose.Html.Dom](../../aspose.html.dom/)
* assembly [Aspose.HTML](../../)
