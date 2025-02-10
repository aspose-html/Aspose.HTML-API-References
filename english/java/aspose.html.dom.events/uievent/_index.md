---
title: UIEvent Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.events.UIEvent class. The UIEvent interface provides specific contextual information associated with User Interface events
type: docs
weight: 1020
url: /java/com.aspose.html.dom.events/uievent/
---
## UIEvent class

The UIEvent interface provides specific contextual information associated with User Interface events.

```java
public class UIEvent : Event
```

## Constructors

| Name | Description |
| --- | --- |
| [UIEvent](uievent/#constructor)(String) | Initializes a new instance of the `UIEvent` class. |
| [UIEvent](uievent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Properties

| Name | Description |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Used to indicate the [`IEventTarget`](../ieventtarget/) whose [`IEventListener`](../ieventlistener/)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Specifies some detail information about the Event, depending on the type of event. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Used to indicate which phase of event flow is currently being evaluated. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Used to indicate the [`IEventTarget`](../ieventtarget/) to which the event was originally dispatched. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) The name of the event (case-insensitive). The name must be an XML name. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) The view attribute identifies the Window from which the event was generated. The un-initialized value of this attribute MUST be null. |

## Methods

| Name | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) method is used to initialize the value of an [`Event`](../event/) created through the[`IDocumentEvent`](../idocumentevent/) interface. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](../event/preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) method is used prevent further propagation of an event during event flow. |

### See Also

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
