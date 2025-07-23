---
title: MouseEvent class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/aspose.html.dom.events/mouseevent/
is_root: false
---

## MouseEvent class

The MouseEvent interface provides specific contextual information associated with Mouse events.



**Inheritance:** [`MouseEvent`](/html/python-net/aspose.html.dom.events/mouseevent) → 
[`UIEvent`](/html/python-net/aspose.html.dom.events/uievent) → 
[`Event`](/html/python-net/aspose.html.dom.events/event) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The MouseEvent type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.dom.events/mouseevent/__init__/#str) | Initializes a new instance of the [`MouseEvent`](/html/python-net/aspose.html.dom.events/mouseevent) class. |


### Properties
| Property | Description |
| :- | :- |
| [bubbles](/html/python-net/aspose.html.dom.events/mouseevent/bubbles) | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [cancelable](/html/python-net/aspose.html.dom.events/mouseevent/cancelable) | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [current_target](/html/python-net/aspose.html.dom.events/mouseevent/current_target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) whose [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)s are currently being processed.<br/>This is particularly useful during capturing and bubbling. |
| [event_phase](/html/python-net/aspose.html.dom.events/mouseevent/event_phase) | Used to indicate which phase of event flow is currently being evaluated. |
| [target](/html/python-net/aspose.html.dom.events/mouseevent/target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) to which the event was originally dispatched. |
| [time_stamp](/html/python-net/aspose.html.dom.events/mouseevent/time_stamp) | Used to specify the time (in milliseconds relative to the epoch) at which the event was created.<br/>Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events.<br/>When not available, a value of 0 will be returned.<br/>Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [type](/html/python-net/aspose.html.dom.events/mouseevent/type) | The name of the event (case-insensitive). The name must be an XML name. |
| [default_prevented](/html/python-net/aspose.html.dom.events/mouseevent/default_prevented) | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [is_trusted](/html/python-net/aspose.html.dom.events/mouseevent/is_trusted) | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [NONE_PHASE](/html/python-net/aspose.html.dom.events/mouseevent/none_phase) | Events not currently dispatched are in this phase. |
| [CAPTURING_PHASE](/html/python-net/aspose.html.dom.events/mouseevent/capturing_phase) | The event is currently being evaluated at the target [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget). |
| [AT_TARGET_PHASE](/html/python-net/aspose.html.dom.events/mouseevent/at_target_phase) | The current event phase is the capturing phase. |
| [BUBBLING_PHASE](/html/python-net/aspose.html.dom.events/mouseevent/bubbling_phase) | The current event phase is the bubbling phase. |
| [view](/html/python-net/aspose.html.dom.events/mouseevent/view) | The view attribute identifies the Window from which the event was generated.<br/>The un-initialized value of this attribute MUST be null. |
| [detail](/html/python-net/aspose.html.dom.events/mouseevent/detail) | Specifies some detail information about the Event, depending on the type of event. |
| [screen_x](/html/python-net/aspose.html.dom.events/mouseevent/screen_x) | The horizontal coordinate at which the event occurred relative to the origin of the screen coordinate system. |
| [screen_y](/html/python-net/aspose.html.dom.events/mouseevent/screen_y) | The vertical coordinate at which the event occurred relative to the origin of the screen coordinate system. |
| [client_x](/html/python-net/aspose.html.dom.events/mouseevent/client_x) | The horizontal coordinate at which the event occurred relative to the viewport associated with the event. |
| [client_y](/html/python-net/aspose.html.dom.events/mouseevent/client_y) | The vertical coordinate at which the event occurred relative to the viewport associated with the event. |
| [ctrl_key](/html/python-net/aspose.html.dom.events/mouseevent/ctrl_key) | Refer to the ctrlKey attribute. |
| [shift_key](/html/python-net/aspose.html.dom.events/mouseevent/shift_key) | Refer to the shiftKey attribute. |
| [alt_key](/html/python-net/aspose.html.dom.events/mouseevent/alt_key) | Refer to the altKey attribute. |
| [meta_key](/html/python-net/aspose.html.dom.events/mouseevent/meta_key) | Refer to the metaKey attribute. |
| [button](/html/python-net/aspose.html.dom.events/mouseevent/button) | During mouse events caused by the depression or release of a mouse button, button MUST be used to indicate which pointer device button changed state. |
| [buttons](/html/python-net/aspose.html.dom.events/mouseevent/buttons) | During any mouse events, buttons MUST be used to indicate which combination of mouse buttons are currently being pressed, expressed as a bitmask. |
| [related_target](/html/python-net/aspose.html.dom.events/mouseevent/related_target) | Used to identify a secondary EventTarget related to a UI event, depending on the type of event. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/html/python-net/aspose.html.dom.events/mouseevent/get_platform_type/#) | This method is used to retrieve the ECMAScript object Type. |
| [init_event](/html/python-net/aspose.html.dom.events/mouseevent/init_event/#str-bool-bool) | The [`Event.init_event`](/html/python-net/aspose.html.dom.events/event/init_event) method is used to initialize the value of an [`Event`](/html/python-net/aspose.html.dom.events/event) created through the<br/>[`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent) interface. |
| [prevent_default](/html/python-net/aspose.html.dom.events/mouseevent/prevent_default/#) | If an event is cancelable, the [`Event.prevent_default`](/html/python-net/aspose.html.dom.events/event/prevent_default) method is used to signify that the event is to be canceled,<br/>meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stop_propagation](/html/python-net/aspose.html.dom.events/mouseevent/stop_propagation/#) | The [`Event.stop_propagation`](/html/python-net/aspose.html.dom.events/event/stop_propagation) method is used prevent further propagation of an event during event flow. |
| [stop_immediate_propagation](/html/python-net/aspose.html.dom.events/mouseevent/stop_immediate_propagation/#) | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |



### See Also
* module [`aspose.html.dom.events`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Event`](/html/python-net/aspose.html.dom.events/event)
* class [`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`MouseEvent`](/html/python-net/aspose.html.dom.events/mouseevent)
* class [`UIEvent`](/html/python-net/aspose.html.dom.events/uievent)
