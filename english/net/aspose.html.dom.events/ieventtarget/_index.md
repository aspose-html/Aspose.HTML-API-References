---
title: IEventTarget Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Events.IEventTarget interface. The EventTarget interface is implemented by all Nodes in an implementation which supports the DOM Event Model. Therefore this interface can be obtained by using binding-specific casting methods on an instance of the Node interface. The interface allows registration and removal of Event Listeners on an EventTarget and dispatch of events to that IEventTarget
type: docs
weight: 980
url: /net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

The [`EventTarget`](../../aspose.html.dom/eventtarget/) interface is implemented by all Nodes in an implementation which supports the DOM Event Model. Therefore, this interface can be obtained by using binding-specific casting methods on an instance of the Node interface. The interface allows registration and removal of Event Listeners on an [`EventTarget`](../../aspose.html.dom/eventtarget/) and dispatch of events to that `IEventTarget`.

```csharp
public interface IEventTarget
```

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | This method allows the registration of event listeners on the event target. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | This method allows the dispatch of events into the implementations event model. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../ieventlistener/) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../ieventlistener/) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |

### See Also

* namespace [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assembly [Aspose.HTML](../../)
