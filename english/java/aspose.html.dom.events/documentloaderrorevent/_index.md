---
title: DocumentLoadErrorEvent Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.events.DocumentLoadErrorEvent class. The DocumentLoadErrorEvent occurres when the requested resource is not available
type: docs
weight: 920
url: /java/com.aspose.html.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

The DocumentLoadErrorEvent occurres when the requested resource is not available.

```java
public class DocumentLoadErrorEvent : ErrorEvent
```

## Properties

| Name | Description |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) The colno attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to zero. It represents the column number where the error occurred in the script. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Used to indicate the [`IEventTarget`](../ieventtarget/) whose [`IEventListener`](../ieventlistener/)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) The error attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to null. Where appropriate, it is set to the object representing the error (e.g. the exception object in the case of an uncaught DOM exception). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Used to indicate which phase of event flow is currently being evaluated. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) The filename attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to the empty String. It represents the absolute URL of the script in which the error originally occurred. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) The lineno attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to zero. It represents the line number where the error occurred in the script. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) The message attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to the empty String. It represents the error message. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Used to indicate the [`IEventTarget`](../ieventtarget/) to which the event was originally dispatched. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) The name of the event (case-insensitive). The name must be an XML name. |

## Methods

| Name | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) method is used to initialize the value of an [`Event`](../event/) created through the[`IDocumentEvent`](../idocumentevent/) interface. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](../event/preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) method is used prevent further propagation of an event during event flow. |

### See Also

* class [ErrorEvent](../errorevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
