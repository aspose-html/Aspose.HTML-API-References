---
title: SVGZoomEvent class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/aspose.html.dom.svg.events/svgzoomevent/
is_root: false
---

## SVGZoomEvent class

The zoom event occurs when the user initiates an action which causes the current view of the SVG document fragment to be rescaled. Event handlers are only recognized on ‘svg’ elements.



**Inheritance:** [`SVGZoomEvent`](/html/python-net/aspose.html.dom.svg.events/svgzoomevent) → 
[`Event`](/html/python-net/aspose.html.dom.events/event) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The SVGZoomEvent type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [bubbles](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/bubbles) | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [cancelable](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/cancelable) | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [current_target](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/current_target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) whose [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)s are currently being processed.<br/>This is particularly useful during capturing and bubbling. |
| [event_phase](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/event_phase) | Used to indicate which phase of event flow is currently being evaluated. |
| [target](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) to which the event was originally dispatched. |
| [time_stamp](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/time_stamp) | Used to specify the time (in milliseconds relative to the epoch) at which the event was created.<br/>Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events.<br/>When not available, a value of 0 will be returned.<br/>Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [type](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/type) | The name of the event (case-insensitive). The name must be an XML name. |
| [default_prevented](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/default_prevented) | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [is_trusted](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/is_trusted) | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [NONE_PHASE](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/none_phase) | Events not currently dispatched are in this phase. |
| [CAPTURING_PHASE](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/capturing_phase) | The event is currently being evaluated at the target [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget). |
| [AT_TARGET_PHASE](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/at_target_phase) | The current event phase is the capturing phase. |
| [BUBBLING_PHASE](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/bubbling_phase) | The current event phase is the bubbling phase. |
| [zoom_rect_screen](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/zoom_rect_screen) | The specified zoom rectangle in screen units.<br/>The SVGRect object is read only. |
| [previous_scale](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/previous_scale) | The scale factor from previous zoom operations that was in place before the zoom operation occurred. |
| [previous_translate](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/previous_translate) | The translation values from previous zoom operations that were in place before the zoom operation occurred.<br/>The SVGPoint object is read only. |
| [new_scale](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/new_scale) | The scale factor that will be in place after the zoom operation has been processed. |
| [new_translate](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/new_translate) | The translation values that will be in place after the zoom operation has been processed.<br/>The SVGPoint object is read only. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [init_event](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/init_event/#str-bool-bool) | The [`Event.init_event`](/html/python-net/aspose.html.dom.events/event/init_event) method is used to initialize the value of an [`Event`](/html/python-net/aspose.html.dom.events/event) created through the<br/>[`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent) interface. |
| [prevent_default](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/prevent_default/#) | If an event is cancelable, the [`Event.prevent_default`](/html/python-net/aspose.html.dom.events/event/prevent_default) method is used to signify that the event is to be canceled,<br/>meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stop_propagation](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/stop_propagation/#) | The [`Event.stop_propagation`](/html/python-net/aspose.html.dom.events/event/stop_propagation) method is used prevent further propagation of an event during event flow. |
| [stop_immediate_propagation](/html/python-net/aspose.html.dom.svg.events/svgzoomevent/stop_immediate_propagation/#) | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |



### See Also
* module [`aspose.html.dom.svg.events`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Event`](/html/python-net/aspose.html.dom.events/event)
* class [`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`SVGZoomEvent`](/html/python-net/aspose.html.dom.svg.events/svgzoomevent)
