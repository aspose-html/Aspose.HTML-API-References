---
title: WheelEvent class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 130
url: /python-net/aspose.html.dom.events/wheelevent/
is_root: false
---

## WheelEvent class

The WheelEvent interface provides specific contextual information associated with wheel events. To create an instance of the WheelEvent interface, use the WheelEvent constructor, passing an optional WheelEventInit dictionary.



**Inheritance:** [`WheelEvent`](/html/python-net/aspose.html.dom.events/wheelevent) → 
[`MouseEvent`](/html/python-net/aspose.html.dom.events/mouseevent) → 
[`UIEvent`](/html/python-net/aspose.html.dom.events/uievent) → 
[`Event`](/html/python-net/aspose.html.dom.events/event) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The WheelEvent type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.dom.events/wheelevent/__init__/#str) | Initializes a new instance of the [`WheelEvent`](/html/python-net/aspose.html.dom.events/wheelevent) class. |


### Properties
| Property | Description |
| :- | :- |
| [bubbles](/html/python-net/aspose.html.dom.events/wheelevent/bubbles) | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [cancelable](/html/python-net/aspose.html.dom.events/wheelevent/cancelable) | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [current_target](/html/python-net/aspose.html.dom.events/wheelevent/current_target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) whose [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)s are currently being processed.<br/>This is particularly useful during capturing and bubbling. |
| [event_phase](/html/python-net/aspose.html.dom.events/wheelevent/event_phase) | Used to indicate which phase of event flow is currently being evaluated. |
| [target](/html/python-net/aspose.html.dom.events/wheelevent/target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) to which the event was originally dispatched. |
| [time_stamp](/html/python-net/aspose.html.dom.events/wheelevent/time_stamp) | Used to specify the time (in milliseconds relative to the epoch) at which the event was created.<br/>Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events.<br/>When not available, a value of 0 will be returned.<br/>Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [type](/html/python-net/aspose.html.dom.events/wheelevent/type) | The name of the event (case-insensitive). The name must be an XML name. |
| [default_prevented](/html/python-net/aspose.html.dom.events/wheelevent/default_prevented) | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [is_trusted](/html/python-net/aspose.html.dom.events/wheelevent/is_trusted) | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [NONE_PHASE](/html/python-net/aspose.html.dom.events/wheelevent/none_phase) | Events not currently dispatched are in this phase. |
| [CAPTURING_PHASE](/html/python-net/aspose.html.dom.events/wheelevent/capturing_phase) | The event is currently being evaluated at the target [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget). |
| [AT_TARGET_PHASE](/html/python-net/aspose.html.dom.events/wheelevent/at_target_phase) | The current event phase is the capturing phase. |
| [BUBBLING_PHASE](/html/python-net/aspose.html.dom.events/wheelevent/bubbling_phase) | The current event phase is the bubbling phase. |
| [view](/html/python-net/aspose.html.dom.events/wheelevent/view) | The view attribute identifies the Window from which the event was generated.<br/>The un-initialized value of this attribute MUST be null. |
| [detail](/html/python-net/aspose.html.dom.events/wheelevent/detail) | Specifies some detail information about the Event, depending on the type of event. |
| [screen_x](/html/python-net/aspose.html.dom.events/wheelevent/screen_x) | The horizontal coordinate at which the event occurred relative to the origin of the screen coordinate system. |
| [screen_y](/html/python-net/aspose.html.dom.events/wheelevent/screen_y) | The vertical coordinate at which the event occurred relative to the origin of the screen coordinate system. |
| [client_x](/html/python-net/aspose.html.dom.events/wheelevent/client_x) | The horizontal coordinate at which the event occurred relative to the viewport associated with the event. |
| [client_y](/html/python-net/aspose.html.dom.events/wheelevent/client_y) | The vertical coordinate at which the event occurred relative to the viewport associated with the event. |
| [ctrl_key](/html/python-net/aspose.html.dom.events/wheelevent/ctrl_key) | Refer to the ctrlKey attribute. |
| [shift_key](/html/python-net/aspose.html.dom.events/wheelevent/shift_key) | Refer to the shiftKey attribute. |
| [alt_key](/html/python-net/aspose.html.dom.events/wheelevent/alt_key) | Refer to the altKey attribute. |
| [meta_key](/html/python-net/aspose.html.dom.events/wheelevent/meta_key) | Refer to the metaKey attribute. |
| [button](/html/python-net/aspose.html.dom.events/wheelevent/button) | During mouse events caused by the depression or release of a mouse button, button MUST be used to indicate which pointer device button changed state. |
| [buttons](/html/python-net/aspose.html.dom.events/wheelevent/buttons) | During any mouse events, buttons MUST be used to indicate which combination of mouse buttons are currently being pressed, expressed as a bitmask. |
| [related_target](/html/python-net/aspose.html.dom.events/wheelevent/related_target) | Used to identify a secondary EventTarget related to a UI event, depending on the type of event. |
| [delta_x](/html/python-net/aspose.html.dom.events/wheelevent/delta_x) | In user agents where the default action of the wheel event is to scroll, the value MUST be the measurement along the x-axis (in pixels, lines, or pages) to be scrolled in the case where the event is not cancelled. Otherwise, this is an implementation-specific measurement (in pixels, lines, or pages) of the movement of a wheel device around the x-axis. |
| [delta_y](/html/python-net/aspose.html.dom.events/wheelevent/delta_y) | In user agents where the default action of the wheel event is to scroll, the value MUST be the measurement along the y-axis (in pixels, lines, or pages) to be scrolled in the case where the event is not cancelled. Otherwise, this is an implementation-specific measurement (in pixels, lines, or pages) of the movement of a wheel device around the y-axis. |
| [delta_z](/html/python-net/aspose.html.dom.events/wheelevent/delta_z) | In user agents where the default action of the wheel event is to scroll, the value MUST be the measurement along the z-axis (in pixels, lines, or pages) to be scrolled in the case where the event is not cancelled. Otherwise, this is an implementation-specific measurement (in pixels, lines, or pages) of the movement of a wheel device around the z-axis. |
| [delta_mode](/html/python-net/aspose.html.dom.events/wheelevent/delta_mode) | The deltaMode attribute contains an indication of the units of measurement for the delta values. The default value is DOM_DELTA_PIXEL (pixels). |
| [DOM_DELTA_PIXEL](/html/python-net/aspose.html.dom.events/wheelevent/dom_delta_pixel) | The units of measurement for the delta MUST be pixels. This is the most typical case in most operating system and implementation configurations. |
| [DOM_DELTA_LINE](/html/python-net/aspose.html.dom.events/wheelevent/dom_delta_line) | The units of measurement for the delta MUST be individual lines of text. This is the case for many form controls. |
| [DOM_DELTA_PAGE](/html/python-net/aspose.html.dom.events/wheelevent/dom_delta_page) | The units of measurement for the delta MUST be pages, either defined as a single screen or as a demarcated page. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/html/python-net/aspose.html.dom.events/wheelevent/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [init_event](/html/python-net/aspose.html.dom.events/wheelevent/init_event/#str-bool-bool) | The [`Event.init_event`](/html/python-net/aspose.html.dom.events/event/init_event) method is used to initialize the value of an [`Event`](/html/python-net/aspose.html.dom.events/event) created through the<br/>[`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent) interface. |
| [prevent_default](/html/python-net/aspose.html.dom.events/wheelevent/prevent_default/#) | If an event is cancelable, the [`Event.prevent_default`](/html/python-net/aspose.html.dom.events/event/prevent_default) method is used to signify that the event is to be canceled,<br/>meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stop_propagation](/html/python-net/aspose.html.dom.events/wheelevent/stop_propagation/#) | The [`Event.stop_propagation`](/html/python-net/aspose.html.dom.events/event/stop_propagation) method is used prevent further propagation of an event during event flow. |
| [stop_immediate_propagation](/html/python-net/aspose.html.dom.events/wheelevent/stop_immediate_propagation/#) | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |



### See Also
* module [`aspose.html.dom.events`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Event`](/html/python-net/aspose.html.dom.events/event)
* class [`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`MouseEvent`](/html/python-net/aspose.html.dom.events/mouseevent)
* class [`UIEvent`](/html/python-net/aspose.html.dom.events/uievent)
* class [`WheelEvent`](/html/python-net/aspose.html.dom.events/wheelevent)
