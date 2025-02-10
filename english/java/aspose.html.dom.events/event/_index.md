---
title: Event Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.events.Event class. The is used to provide contextual information about an event to the handler processing the event
type: docs
weight: 940
url: /java/com.aspose.html.dom.events/event/
---
## Event class

The is used to provide contextual information about an event to the handler processing the event.

```java
public class Event : DOMObject
```

## Constructors

| Name | Description |
| --- | --- |
| [Event](event/#constructor)(String) | Initializes a new instance of the `Event` class. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Properties

| Name | Description |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Used to indicate the [`IEventTarget`](../ieventtarget/) whose [`IEventListener`](../ieventlistener/)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Used to indicate which phase of event flow is currently being evaluated. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Used to indicate the [`IEventTarget`](../ieventtarget/) to which the event was originally dispatched. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) The name of the event (case-insensitive). The name must be an XML name. |

## Methods

| Name | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](./initevent/) method is used to initialize the value of an `Event` created through the[`IDocumentEvent`](../idocumentevent/) interface. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](./preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](./stoppropagation/) method is used prevent further propagation of an event during event flow. |

## Fields

| Name | Description |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | The current event phase is the capturing phase. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | The current event phase is the bubbling phase. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | The event is currently being evaluated at the target [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | Events not currently dispatched are in this phase. |

## Remarks

An object which implements the is generally passed as the first parameter to an event handler. More specific context information is passed to event handlers by deriving additional interfaces from which contain information directly relating to the type of event they accompany. These derived interfaces are also implemented by the object passed to the event listener.

### See Also

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
