---
title: DocumentLoadErrorEvent
second_title: Aspose.HTML for .NET API Reference
description: The DocumentLoadErrorEvent occurres when the requested resource is not available.
type: docs
weight: 870
url: /net/aspose.html.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

The DocumentLoadErrorEvent occurres when the requested resource is not available.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Properties

| Name | Description |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [ColNo](../../aspose.html.dom.events/errorevent/colno) { get; } | The colno attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to zero. It represents the column number where the error occurred in the script. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Used to indicate the [`IEventTarget`](../ieventtarget) whose [`IEventListener`](../ieventlistener)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [Error](../../aspose.html.dom.events/errorevent/error) { get; } | The error attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to null. Where appropriate, it is set to the object representing the error (e.g. the exception object in the case of an uncaught DOM exception). |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Used to indicate which phase of event flow is currently being evaluated. |
| [FileName](../../aspose.html.dom.events/errorevent/filename) { get; } | The filename attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to the empty string. It represents the absolute URL of the script in which the error originally occurred. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno) { get; } | The lineno attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to zero. It represents the line number where the error occurred in the script. |
| [Message](../../aspose.html.dom.events/errorevent/message) { get; } | The message attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to the empty string. It represents the error message. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Used to indicate the [`IEventTarget`](../ieventtarget) to which the event was originally dispatched. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | The name of the event (case-insensitive). The name must be an XML name. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | This method is used to retrieve the ECMAScript object . |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | The [`InitEvent`](../event/initevent) method is used to initialize the value of an [`Event`](../event) created through the[`IDocumentEvent`](../idocumentevent) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | If an event is cancelable, the [`PreventDefault`](../event/preventdefault) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | The [`StopPropagation`](../event/stoppropagation) method is used prevent further propagation of an event during event flow. |

### See Also

* class [ErrorEvent](../errorevent)
* namespace [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
