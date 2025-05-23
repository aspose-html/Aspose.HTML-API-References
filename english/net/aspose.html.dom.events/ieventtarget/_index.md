---
title: IEventTarget Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Events.IEventTarget interface. The EventTarget interface is implemented by all Nodes in an implementation which supports the DOM Event Model. Therefore this interface can be obtained by using binding-specific casting methods on an instance of the Node interface. The interface allows registration and removal of Event Listeners on an and dispatch of events to that
type: docs
weight: 980
url: /net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

The EventTarget interface is implemented by all Nodes in an implementation which supports the DOM Event Model. Therefore, this interface can be obtained by using binding-specific casting methods on an instance of the Node interface. The interface allows registration and removal of Event Listeners on an and dispatch of events to that.

```csharp
public interface IEventTarget
```

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | The EventTarget method addEventListener() sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | The EventTarget method addEventListener() sets up a function that will be called whenever the specified event is delivered to the target. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | Dispatches an Event at the specified EventTarget, (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with dispatchEvent(). |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |

### See Also

* namespace [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assembly [Aspose.HTML](../../)
