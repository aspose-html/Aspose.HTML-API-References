---
title: SVGZoomEvent
second_title: Aspose.HTML for .NET API Reference
description: The zoom event occurs when the user initiates an action which causes the current view of the SVG document fragment to be rescaled. Event handlers are only recognized on svg elements.
type: docs
weight: 1330
url: /net/aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

The zoom event occurs when the user initiates an action which causes the current view of the SVG document fragment to be rescaled. Event handlers are only recognized on ‘svg’ elements.

```csharp
public class SVGZoomEvent : Event
```

## Properties

| Name | Description |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Used to indicate the [`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) whose [`IEventListener`](../../aspose.html.dom.events/ieventlistener/)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Used to indicate which phase of event flow is currently being evaluated. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [NewScale](../../aspose.html.dom.svg.events/svgzoomevent/newscale/) { get; } | The scale factor that will be in place after the zoom operation has been processed. |
| [NewTranslate](../../aspose.html.dom.svg.events/svgzoomevent/newtranslate/) { get; } | The translation values that will be in place after the zoom operation has been processed. The SVGPoint object is read only. |
| [PreviousScale](../../aspose.html.dom.svg.events/svgzoomevent/previousscale/) { get; } | The scale factor from previous zoom operations that was in place before the zoom operation occurred. |
| [PreviousTranslate](../../aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) { get; } | The translation values from previous zoom operations that were in place before the zoom operation occurred. The SVGPoint object is read only. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Used to indicate the [`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) to which the event was originally dispatched. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | The name of the event (case-insensitive). The name must be an XML name. |
| [ZoomRectScreen](../../aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) { get; } | The specified zoom rectangle in screen units. The SVGRect object is read only. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | The [`InitEvent`](../../aspose.html.dom.events/event/initevent/) method is used to initialize the value of an [`Event`](../../aspose.html.dom.events/event/) created through the[`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) method is used prevent further propagation of an event during event flow. |

### See Also

* class [Event](../../aspose.html.dom.events/event/)
* namespace [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
