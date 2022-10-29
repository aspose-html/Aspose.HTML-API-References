---
title: MouseEvent
second_title: Aspose.HTML for .NET API Reference
description: The MouseEvent interface provides specific contextual information associated with Mouse events.
type: docs
weight: 840
url: /net/aspose.html.dom.events/mouseevent/
---
## MouseEvent class

The MouseEvent interface provides specific contextual information associated with Mouse events.

```csharp
public class MouseEvent : UIEvent
```

## Constructors

| Name | Description |
| --- | --- |
| [MouseEvent](mouseevent#constructor)(string) | Initializes a new instance of the [`MouseEvent`](./mouseevent/) class. |
| [MouseEvent](mouseevent#constructor_1)(string, IDictionary&lt;string, object&gt;) |  |

## Properties

| Name | Description |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | Refer to the altKey attribute. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | During mouse events caused by the depression or release of a mouse button, button MUST be used to indicate which pointer device button changed state. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | During any mouse events, buttons MUST be used to indicate which combination of mouse buttons are currently being pressed, expressed as a bitmask. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | The horizontal coordinate at which the event occurred relative to the viewport associated with the event. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | The vertical coordinate at which the event occurred relative to the viewport associated with the event. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | Refer to the ctrlKey attribute. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Used to indicate the [`IEventTarget`](../ieventtarget/) whose [`IEventListener`](../ieventlistener/)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Specifies some detail information about the Event, depending on the type of event. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Used to indicate which phase of event flow is currently being evaluated. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | Refer to the metaKey attribute. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | Used to identify a secondary EventTarget related to a UI event, depending on the type of event. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | The horizontal coordinate at which the event occurred relative to the origin of the screen coordinate system. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | The vertical coordinate at which the event occurred relative to the origin of the screen coordinate system. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | Refer to the shiftKey attribute. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Used to indicate the [`IEventTarget`](../ieventtarget/) to which the event was originally dispatched. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | The name of the event (case-insensitive). The name must be an XML name. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | The view attribute identifies the Window from which the event was generated. The un-initialized value of this attribute MUST be null. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | The [`InitEvent`](../event/initevent/) method is used to initialize the value of an [`Event`](../event/) created through the[`IDocumentEvent`](../idocumentevent/) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](../event/preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) method is used prevent further propagation of an event during event flow. |

### See Also

* class [UIEvent](../uievent/)
* namespace [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
