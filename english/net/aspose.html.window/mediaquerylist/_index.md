---
title: MediaQueryList Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Window.MediaQueryList class. A MediaQueryList object stores information on a media query applied to a document with support for both immediate and event-driven matching against the state of the document. See CSSOM View Module specification https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface
type: docs
weight: 6140
url: /net/aspose.html.window/mediaquerylist/
---
## MediaQueryList class

A MediaQueryList object stores information on a media query applied to a document, with support for both immediate and event-driven matching against the state of the document. See CSSOM View Module specification: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.html.window/mediaquerylist/document/) { get; } | Context object's associated document. |
| [Matches](../../aspose.html.window/mediaquerylist/matches/) { get; } | A boolean value that returns true if the document currently matches the media query list, or false if not. |
| [Media](../../aspose.html.window/mediaquerylist/media/) { get; } | A string representing a serialized media query. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | The addEventListener() method of the [`EventTarget `](../../aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddListener](../../aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Add MediaQueryList matches state change event listener. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveListener](../../aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Remove MediaQueryList matches state change event listener. |

## Events

| Name | Description |
| --- | --- |
| event [OnChange](../../aspose.html.window/mediaquerylist/onchange/) | Event that is fired at the MediaQueryList when the matches state changes. |

### See Also

* class [EventTarget](../../aspose.html.dom/eventtarget/)
* namespace [Aspose.Html.Window](../../aspose.html.window/)
* assembly [Aspose.HTML](../../)
